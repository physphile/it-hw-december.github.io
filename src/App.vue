<template>
  <div id="app">
    <Header />
    <Content
      v-bind:papers='papers'
    />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Content from '@/components/Content.vue'
export default {
  name: 'App',
  data() {
    return {
      papers: [
        {paperTitle: "Initial Paper", paperAuthor: "physfeel", paperDate: "2020/12/8"}
      ]
    }
  },
  components: {
    Header, Content
  }
}
</script>

<style>
* {
  margin: 0;
}
</style>
