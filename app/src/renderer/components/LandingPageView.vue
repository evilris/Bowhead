<template>
  <div>
    <img src="./LandingPageView/assets/logo.png" alt="electron-vue">
    <h1>GUI for</h1>
    <img src="./LandingPageView/assets/docker.png" width="80%" height="80%">
  </div>
</template>

<script>
  import CurrentPage from './LandingPageView/CurrentPage';
  import Links from './LandingPageView/Links';
  import Versions from './LandingPageView/Versions';
  export default {
    components: {
      CurrentPage,
      Links,
      Versions,
    },
    name: 'landing-page',
  };
</script>

<style scoped>
  img {
    margin-top: -25px;
    width: 450px;
  }
</style>
