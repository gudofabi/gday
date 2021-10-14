<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <Navigation />
    <router-view/>
    <Footer />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation';
import Footer from '@/components/Footer';
export default {
  name: "App",
  components: {
    Navigation,
    Footer
  }
}
</script>
