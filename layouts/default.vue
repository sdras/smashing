<template>
  <div>
    <app-nav/>
    <nuxt/>
  </div>
</template>

<script>
import AppNav from "~/components/AppNav.vue";

export default {
  components: {
    AppNav
  }
};
</script>


<style>
html {
  font-family: "Roboto", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #0b0d17;
  color: #eee;
}

a,
a:visited,
a:active {
  color: white;
  text-decoration: none;
}

h1,
h2,
h3 {
  font-family: "Alfa Slab One", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-weight: normal;
}

h1 {
  font-weight: 45px;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>
