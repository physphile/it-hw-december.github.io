<template>
  <div class="header">
    <h1 class="headerTitle">LangWatch</h1>
    <headerMenu />
  </div>
</template>

<script>
import headerMenu from "@/components/headerMenu.vue";
export default {
  components: {
    headerMenu,
  },
};
</script>

<style scoped>
.header {
  height: 200px;
  width: 100%;
  display: flex;

  align-items: center;
  box-shadow: 0 20px 20px rgba(0, 0, 0, 0.2);
  margin-bottom: 40px;
}
.headerTitle {
    font-family: monospace;
    font-size: 5rem;
    margin: 2rem;
    }
</style>
