<template>
  <!-- Navbar Light -->

  <nav
    class="navbar navbar-expand-lg navbar-lg bs-blue navbar-white z-index-3 py-3"
  >
    <div class="container">
      <a
        class="navbar-brand"
        href="/"
        rel="tooltip"
        title="Designed and Coded by Creative Tim"
        data-placement="bottom"
      >
        Bootstrap Vue
      </a>
      <a
        href="#"
        class="btn btn-sm bg-gradient-primary btn-round mb-0 ms-auto d-lg-none d-block"
        >Buy Now</a
      >
      <button
        class="navbar-toggler shadow-none ms-2"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navigation"
        aria-controls="navigation"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon mt-2">
          <span class="navbar-toggler-bar bar1"></span>
          <span class="navbar-toggler-bar bar2"></span>
          <span class="navbar-toggler-bar bar3"></span>
        </span>
      </button>
      <div
        class="collapse navbar-collapse w-100 pt-3 pb-2 py-lg-0"
        id="navigation"
      >
        <ul class="navbar-nav navbar-nav-hover mx-auto">
          <li class="nav-item mx-2">
            <RouterLink
              to="/"
              class="nav-link ps-2 d-flex justify-content-between cursor-pointer align-items-center"
              role="button"
            >
              Home
            </RouterLink>
          </li>

          <li class="nav-item mx-2">
            <RouterLink
              to="/docs"
              class="nav-link ps-2 d-flex justify-content-between cursor-pointer align-items-center"
              role="button"
            >
              Docs
            </RouterLink>
          </li>
          <li class="nav-item mx-2">
            <RouterLink
              to="/about"
              class="nav-link ps-2 d-flex justify-content-between cursor-pointer align-items-center"
              role="button"
            >
              About
            </RouterLink>
          </li>

          <li class="nav-item mx-2">
            <RouterLink
              to="/blog"
              class="nav-link ps-2 d-flex justify-content-between cursor-pointer align-items-center"
              role="button"
            >
              Blog
            </RouterLink>
          </li>
        </ul>

        <ul class="navbar-nav d-lg-block d-none">
          <li class="nav-item">
            <a
              href="#"
              class="btn btn-sm bg-gradient-primary mb-0 me-1"
              role="button"
              ><img src="./icons/github.png" alt=""
            /></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- End Navbar -->
</template>

<script>
import { RouterLink } from "vue-router";
export default {
  name: "BootstrapvueNavBar",
  components: {
    RouterLink,
  },

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped></style>
