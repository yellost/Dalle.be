<template>
  <div>
    <HomeHeader/>
    <HomeMain/>
  <Footer/>
  </div>


</template>

<script>
// @ is an alias to /src
import HomeHeader from '@/components/HomeHeader.vue'
import HomeMain from '@/components/HomeMain.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeMain,
    Footer
  }
}
</script>
