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
        {title: "Initial Paper", author: "physfeel", date: "2020/12/8"},
        {title: "Языки для души", author: "rabriva", date: "2020/12/7"},
        {title: "Топ эзотерических языков", author: "rabriva", date: "2020/12/6"},
        {title: "Привет, мир!", author: "physfeel", date: "2020/12/5"}
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
