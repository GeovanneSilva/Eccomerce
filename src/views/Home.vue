<template>
  <v-app>
    <navbar class="index" />
    <dashboard />
    <Footer></Footer>
  </v-app>
</template>

<script>
import Dashboard from '../components/Dashboard.vue';
import Navbar from '../components/Navbar.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Dashboard,
    Navbar,
    Footer,
  },
};
</script>
