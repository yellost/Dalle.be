<template>
  <div>
    <Header Page="Home"/>
    <RestoList :restoList="RestoList"/>
    <Footer/>
  </div>


</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import RestoList from '@/components/RestoList.vue';
import Footer from '@/components/Footer.vue';

import axios from 'axios';

export default {
  data(){
      return {
          RestoList: []
      }
  },
  created(){
      axios.get("http://bd-restaurant.azurewebsites.net/api/Restaurants/GetRestaurants")
      .then(response => {
          this.RestoList = response.data;
      })
  },
  name: 'Home',
  components: {
    Header,
    RestoList,
    Footer
  }
}
</script>
