<template>
  <div id="app">
    <AppNavBar />
    <AppHeader />
    <Needed />
    <SpecApp />
    <Footer />
  </div>
</template>

<script>
import AppNavBar from "./components/app-navbar.vue";
import AppHeader from "./components/app-header.vue";
import Needed from "./components/app-needed.vue";
import SpecApp from "./components/app-specialApps.vue";
import Footer from "./components/app-footer.vue";
export default {
  name: "App",
  components: {
    AppNavBar,
    AppHeader,
    Needed,
    SpecApp,
    Footer,
  },
  
};

</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Cairo&family=Lato:ital,wght@0,300;0,400;0,700;1,300;1,400&family=Montserrat:wght@500&display=swap");

#app {
  direction: rtl !important;
  text-align: right;
  font-family:'Cairo', sans-serif; 
}
</style>
