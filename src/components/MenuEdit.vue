<template>
    <div>
<MenuForm/>
<MenuList/>
    </div>
</template>

<script>

import MenuForm from "@/components/MenuForm.vue";
import MenuList from "@/components/MenuList.vue";



export default {
 name: "MenuEdit",
  components: {
    MenuForm,
    MenuList
  }
}
</script>

<style>

</style>
