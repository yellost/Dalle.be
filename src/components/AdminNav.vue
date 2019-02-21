<template>
    <div>
        <Header/>
         <div class="top-bar">
        <form>
            <input type="image" src="img/loupe.png" name="Submit" />
            <input type="search" name='q' placeholder="Nom, code postal, cuisine">
        </form>
        <button class="add">Ajouter</button>
    </div>

        <Footer/>
    </div>

</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
name: 'AdminNav',
  components: {
    Header,
    Footer,
  }

}
</script>

<style>
.restoAdmin {
    position: relative;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;}
    .top-bar {
        width: 80%;
        display: flex;
        justify-content: flex-start;
    }

    form {
        display: flex;
        margin-right: 30px;
    }
    input[type="image"] {
        width: 20px;
        height: 20px;
        background-color: #f00;
        border-radius: 5px;
        padding: 10px;
        box-sizing: content-box;
    }
    input[type="search"] {
        width: 250px;
        height: 20px;
        border-radius: 5px;
        padding: 10px;
        box-sizing: content-box;
        border:none;
        margin-left: 5px;
    }
    .restaurant-list{
        margin-top:50px;
        border-top:1px solid red;
        width: 80%;
        height: 65vh;
        border-bottom:1px solid red;
        margin-right:50px;
        overflow: scroll;
        overflow-x: hidden;}
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            height: 100%;
        }
        .restaurant-data{
            width:90%;
            height:50px;
            border-bottom:1px solid rgb(165, 165, 165);
            display: flex;
            justify-content: space-between;
            align-items: center;}
            img{
                display: inline-block;
                width:30px;
                height:30px;
            }
        
    

</style>
