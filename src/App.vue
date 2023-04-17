<template>
  <div>
    <!-- <FirstComponent msg="Hi Dhruv " /> -->
    <HelloWorld msg=" App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
// import HomeComponent from "./components/HomeComponent.vue";
// import FirstComponent from "./components/FirstComponent.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    // FirstComponent,
  },
};
</script>

<style></style>
