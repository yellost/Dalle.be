<template>

    <div>
<Header/>
<div class="container">
<MenuListItem/>
</div>
    </div>
</template>

<script>
import Header from "@/components/Header.vue";
import MenuListItem from "@/components/MenuForm.vue";

export default {
name: "MenuList",
  components: {
      Header,
    MenuListItem
  }
}
</script>

<style>

</style>
