<template>
  <Header></Header>
  <router-view />
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: { Header },
};
</script>

<style lang="scss">
body {
  margin: 0;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

* {
  box-sizing: border-box;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
  font-family: "Varela Round", sans-serif;
}

body,
p {
  font-family: "Nunito Sans", sans-serif;
}
</style>
