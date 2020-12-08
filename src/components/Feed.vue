<template>
  <div>
   <Card
   v-for="paper in papers " :key="paper.message"
   v-bind:paper="paper" 
   />
   
  </div>
</template>
<script>
import Card from "@/components/Card.vue";
export default {
    props: [
        'papers'
    ],
  components: {
    Card,
  },
};
</script>

<style scoped>
</style>