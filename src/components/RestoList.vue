<template>
    <div class="pagecenter">
        <RestoEntry  v-for="(resto,index) in restoList" :key='index' :resto="resto"/>
    </div>
</template>

<script>
// @ is an alias to /src
import RestoEntry from '@/components/RestoEntry.vue';

export default {
  name: 'HomeHeader',
  components: {
      RestoEntry
  },
  props: ["restoList"]
}
</script>


<style>

.pageCenter{
    display: flex;
    justify-content: center;
}

</style>
