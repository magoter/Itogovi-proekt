<template>
  <HeaderComponent></HeaderComponent>
  <MainComponent></MainComponent>
</template>

<script>
import MainComponent from "./grandParentComponents/Main.vue";
import HeaderComponent from "./grandParentComponents/Header.vue";

export default {
  name: 'App',
  components:{
    MainComponent, 
    HeaderComponent, 

  }
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 1400px;
  display: flex;
  justify-content: center;
}

</style>
