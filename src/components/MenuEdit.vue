<template>
    <div>
        <Header/>
<MenuForm/>
<MenuList/>
    </div>
</template>

<script>
import Header from "@/components/Header.vue";
import MenuForm from "@/components/MenuForm.vue";
import MenuList from "@/components/MenuList.vue";



export default {
 name: "MenuEdit",
  components: {
      Header,
    MenuForm,
    MenuList
  }
}
</script>

<style>

</style>
