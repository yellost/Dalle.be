
<template>
    <div class="post">
        <div class="imgResto">
            <img src="~@/assets/img/steak.gif" alt="">
        </div>
        <div class="info">
            <router-link :to="'/Resto/' + resto.RestaurantID"><h3>{{resto.Name}}</h3></router-link>
            
            <p>{{resto.Description}}</p>
        </div>
    </div>
</template>

<script>
// @ is an alias to /src

export default {
  props: ["resto"]
}
</script>