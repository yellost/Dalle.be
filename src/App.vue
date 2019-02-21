<template>
  <div id="app" class="jesaispas">

    <p>BOUMMMMMMMMMMMMM!!!!!!!</p>
      <router-link to="/home">Home</router-link> |
      <router-link to="/resto">Resto</router-link> |
      <router-link to="/admin">Admin</router-link>
    <router-view/>
    

    <footer>
        <div class="logoFoot">
            <img src="~@/assets/img/logo.png" alt="">
        </div>
        <p>info@dalle.be</p>
    </footer>

  </div>
</template>

<style>
 @import './assets/css/style.min.css'
</style>
