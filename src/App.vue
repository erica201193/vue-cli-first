<template>
  <div>
    <JumboTron></JumboTron>
    <PageTitle></PageTitle>


  </div>
</template>

<script>
import PageTitle from './components/PageTitle.vue';
import JumboTron from '../components/JumboTron.vue';

export default {
  components: {
    PageTitle, JumboTron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
