<template>
  <div class="home">
    <img
      alt="Dedication logo"
      src="../assets/dedication-logo.jpg"
      style="width: 300px; height: 300px"
    />
    <HelloWorld msg="Go Dedication" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
