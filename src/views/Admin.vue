<template>
  <div>
    <Header/>
    <AdminMain/>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import AdminMain from '@/components/AdminMain.vue'

export default {
  name: 'Admin',
  components: {
    Header,
    Footer,
    AdminMain
  }
}
</script>

<style>

</style>
