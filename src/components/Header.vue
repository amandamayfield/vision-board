<template>
  <div class="header">
    <router-link to="/" class="header-item">Home</router-link>
    <router-link to="/add" class="header-item">Add Trip</router-link>
  </div>
</template>

<script>
export default {
  name: "Header",
  setup() {
    return {};
  },
};
</script>

<style lang="scss">
.header {
  background-color: #e3e3e3;
  padding: 20px;
  &-item {
    text-decoration: none;
    color: black;
    cursor: pointer;
    font-size: 20px;
    padding: 0 10px;
    &:hover {
      color: #555555;
    }
  }
}
</style>
