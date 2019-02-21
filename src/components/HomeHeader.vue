<template>
<header>
    <img src="img/logo2.png" alt="" class="logo">
    <div class="boutons">
        <button type="submit" form="form1" value="Submit">Log in</button>
        <button type="submit" form="form1" value="Submit">Sign in</button>
    </div>
    <div class="formHolder">
        <form action="post" id="form1">
            <button type="submit" form="form1" value="Submit"><img src="~@/assets/img/loupe.png"></button>
            <input type="text" name="search" placeholder="Nom du resto, adresse,...">
        </form>
    </div>
</header>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeHeader',
  components: {
  }
}
</script>