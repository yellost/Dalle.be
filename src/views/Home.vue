<template>
  <div>
    <HomeHeader/>
    <HomeMain/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeHeader from '@/components/HomeHeader.vue'
import HomeMain from '@/components/HomeMain.vue'

export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeMain,
  }
}
</script>
