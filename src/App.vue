<template>
  <div class="container">
    <Header />
    <Home />
  </div>
</template>
<script>
import Header from "./components/Header.vue";
import Home from "./views/Home.vue"
export default {
  components: {
    Header,
    Home
  },
};
</script>
