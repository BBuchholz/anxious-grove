<template>
  <div class="myriad">
    <MyriadLinks />
    <!-- <img
      alt="A Technician In A Cyberpunk Occult Style Working On An Engine"
      src="../assets/Imagine_Occult-Technician_with-stamp.jpg"
    /> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import MyriadLinks from "@/components/MyriadLinks.vue"; // @ is an alias to /src

export default defineComponent({
  name: "MyriadView",
  components: {
    MyriadLinks,
  },
});
</script>
