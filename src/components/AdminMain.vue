<template>
    <div>
        <Header/>
        <AdminNav/>
        <AdminList/>
        <Footer/>


    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import AdminNav from '@/components/AdminNav.vue'
import AdminList from '@/components/AdminList.vue'
export default {
name: 'AdminMain',
  components: {
    Header,
    Footer,
    AdminNav,
    AdminList
  }

}
</script>

<style>

</style>
