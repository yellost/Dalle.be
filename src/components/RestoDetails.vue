<template>
  
  <article>
    <div class="restoInfo">
      <div class="imgPlat">
        <img src="img/table4.jpg" alt="#">
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
  </article>
  
</template>

<script>

import axios from 'axios';

export default {
  data(){
      return {
          resto: {}
      }
  },
  created(){
      axios.get("http://bd-restaurant.azurewebsites.net/api/Restaurants/GetRestaurantById/"+this.$route.params.id)
      .then(response => {
          this.resto = response.data;
      })
  },
  name: "RestoDetails"
}
</script>
