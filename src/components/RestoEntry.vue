
<template>
    <div class="post">
        <div class="imgResto">
            <img src="~@/assets/img/steak.gif" alt="">
        </div>
        <div class="info">
            <h3>{{resto.Name}}</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quaerat, ab. </p>
        </div>
    </div>
</template>

<script>
// @ is an alias to /src

export default {
  props: ["resto"]
}
</script>