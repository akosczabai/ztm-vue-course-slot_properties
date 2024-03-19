<template>
  <div id="app">
    <hello-world #default="{ user, favourites }">
      <p>Hello {{ user.name }}. I like {{ favourites[0] }}</p>
    </hello-world>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>
