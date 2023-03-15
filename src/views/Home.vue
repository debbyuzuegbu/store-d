<template>
  <v-app>
    <Navbar class="index" />
    <Dashboard />
    <Footer />
  </v-app>
</template>
  
  <script>
import Navbar from "../components/NavBar";
import Dashboard from "../components/Dashboard";
import Footer from "../components/Footer";
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Home",
  components: {
    Navbar,
    Dashboard,
    Footer,
  },
};
</script>
  <style scoped>
.index {
  z-index: 9999;
}
</style>