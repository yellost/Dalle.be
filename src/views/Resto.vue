<template>
  <div>
    <Header/>
    <RestoDetails/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import RestoDetails from "@/components/RestoDetails.vue";

export default {
  name: "Resto",
  components: {
    Header,
    Footer,
    RestoDetails
  }
};
</script>
