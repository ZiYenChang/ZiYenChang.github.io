<template>
  <Navbar />
  <div class="mx-3">
    <MainPage />
  </div>
  
</template>

<script>
import MainPage from './components/MainPage.vue';
import Navbar from './components/Navbar.vue';

export default{
  components:{
    MainPage,
    Navbar,
  },
}
</script>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
