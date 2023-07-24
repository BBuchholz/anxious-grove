<template>
  <div class="thabook">
    <ThaBookLinks />
    <!-- <img
      alt="A Technician In A Cyberpunk Occult Style Working On An Engine"
      src="../assets/Imagine_Occult-Technician_with-stamp.jpg"
    /> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import ThaBookLinks from "@/components/ThaBookLinks.vue"; // @ is an alias to /src

export default defineComponent({
  name: "ThaBookView",
  components: {
    ThaBookLinks,
  },
});
</script>
