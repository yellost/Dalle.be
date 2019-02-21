   <template>
       <div>
        <Header/>
        <AdminListItem/>
  

        <Footer/>
    </div>
   </template>
   
   <script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import AdminListItem from '@/components/AdminListItem.vue'


export default {
name: 'AdminList',
  components: {
    Header,
    AdminListItem,
    Footer
  }

}
   </script>
   
   <style>
   
   </style>
   