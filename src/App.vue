<template>
  <main class="main container">
    <navbar />
    <current />
  </main>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Current from './components/Current.vue';

export default {
  name: "App",
  components: {
    Navbar,
    Current
  }
}
</script>