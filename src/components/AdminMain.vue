<template>
    <div>
        
        <AdminNav/>
        <AdminList/>
        


    </div>
</template>

<script>

import AdminNav from '@/components/AdminNav.vue'
import AdminList from '@/components/AdminList.vue'
export default {
name: 'AdminMain',
  components: {
    AdminNav,
    AdminList
  }

}
</script>

<style>


</style>
