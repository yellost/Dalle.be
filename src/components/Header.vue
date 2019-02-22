<template>
<header>
  <div>
      <LogoLarge/>
      
    
      <ButtonsMain/>
      <SearchBar/>
  </div>
  <div>
      <LogoSmall/>
      <ButtonsAdmin/>
  </div>
</header>
</template>

<script>
// @ is an alias to /src
import LogoLarge from '@/components/LogoLarge.vue'
import LogoSmall from '@/components/LogoSmall.vue'
import ButtonsMain from '@/components/ButtonsMain.vue'
import ButtonsAdmin from '@/components/ButtonsAdmin.vue'
import SearchBar from '@/components/SearchBar.vue'

export default {
  name: 'Home',
  components: {
    LogoLarge,
    SearchBar,
    ButtonsMain,
    LogoSmall,
    ButtonsAdmin
  }
}
</script>