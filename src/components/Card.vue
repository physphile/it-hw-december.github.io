<template>
  <div>
    <h1>{{paper.title}}</h1>
    <h4>{{paper.author}}</h4>
   {{paper.date}}
  </div>
</template>
<script>
export default {
  props: {
      paper: {
          type: Object,
          required: true
      }
  }
 
};
</script>
<style scoped>

</style>