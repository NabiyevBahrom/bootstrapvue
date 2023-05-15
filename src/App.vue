<template>
  <div>
    <NavBar />
    <RouterView />
    <Footer />
  </div>
</template>

<script>
import RouterView from "vue-router";
import NavBar from "./nav/NavBar.vue";
import Footer from "./views/FooterView.vue";
export default {
  name: "BootstrapvueApp",
  components: {
    RouterView,
    NavBar,
    Footer,
  },
  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped></style>
