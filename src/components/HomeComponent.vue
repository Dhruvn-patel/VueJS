<template>
  <div class="home">
    <h1>Home Component</h1>
    <UsersComponent />
  </div>
</template>

<script>
import UsersComponent from "./UsersComponent.vue";
export default {
  name: "HomeComponent",
  components: {
    UsersComponent,
  },
};
</script>

<style>
.home {
  background-color: bisque;
  height: 1000px;
}
</style>
