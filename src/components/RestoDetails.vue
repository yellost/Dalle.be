<template>
  
  <article>
    <div class="restoInfo">
      <div class="imgPlat">
        <img :src="resto.Menu[2].Picture" alt="#">
      </div>
      <div class="infoResto">
        <h3>{{resto.Name}}</h3>
        <p>{{resto.Description}}</p>
      </div>
    </div>
    <div class="contactResto">
      <p>{{resto.Adresse.Street}},  {{resto.Adresse.Number}}</p>
      <p>{{resto.Adresse.Zipcode}} - {{resto.Adresse.City}}</p>
      <p>{{resto.Telephone}}</p>
    </div>
    <MenuListItem v-for="(menuItem, index) in menuList" :key="index"/>
  </article>
  
</template>

<script>

import axios from 'axios';
import MenuListItem from '@/components/MenuListItem.vue';

export default {
  data(){
      return {
          resto: {},
          menuList:[]
      }
  },
  created(){
      axios.get("//bd-restaurant.azurewebsites.net/api/Restaurants/GetRestaurantById/"+this.$route.params.id)
      .then(response => {
          this.resto = response.data;
          this.menuList = this.resto.Menu;
      })
  },
  components: {
    MenuListItem
  },
  name: "RestoDetails"
}
</script>
