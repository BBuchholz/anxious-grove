<template>
  <div class="home">
    <HelloWorld msg="WELLcome 2 thaGARDIN" />
    <img alt="GARDIN Grove logo" src="../assets/MDMDM_LOGO_FIRST.png" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>

<style>
img {
  max-width: 100%;
  height: auto;
}
</style>
