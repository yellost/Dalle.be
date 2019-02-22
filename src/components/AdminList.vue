   <template>
       <div>
        <AdminListItem/>
        <Footer/>
    </div>
   </template>
   
   <script>

import Footer from '@/components/Footer.vue'
import AdminListItem from '@/components/AdminListItem.vue'


export default {
name: 'AdminList',
  components: {
   
    AdminListItem,
    Footer
  }

}
   </script>
   
   <style>
   
   </style>
   