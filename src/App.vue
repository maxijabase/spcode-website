<template>
  <Navbar/>
  <Title style="padding-top:10px" />
  <Slideshow style="margin:20px"/>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Slideshow from './components/Slideshow.vue';
import Title from "./components/Title.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    Title,
    Slideshow
  }
};
</script>

<style>

html {
  background-color: #252525;
}

#app {
  background-color: #252525;
}
</style>
