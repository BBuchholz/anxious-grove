<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      ... ov
      <a href="https://truthfully-cyclopean-barracks.netlify.app/"
        >Our BA ov LG</a
      >
      MyriaD sites
    </p>
    <ul>
      <li>
        <a href="https://madamadam.netlify.app/">MADAMADAM</a>
        (NEW!)
      </li>
      <li>
        <a href="https://papaya-parfait-8fcafc.netlify.app/"
          >AWLWA CarteoGraphy (TEMP HOME)</a
        >
        (NEW!)
      </li>
      <li>
        <a href="https://furiously-visionary-altar.netlify.app/"
          >Shepton Transmission Services</a
        >
      </li>
      <li>
        <a href="https://truthfully-cyclopean-barracks.netlify.app/"
          >Coventry Grove Builders Association</a
        >
      </li>
      <li><a href="https://nameless-star.netlify.app/">Sonic Circle</a></li>
      <li>
        <a href="https://extremely-daemonic-gate.netlify.app/"
          >Jacob's Salvage</a
        >
      </li>
      <li>
        <a href="https://fearlessly-artifactual.netlify.app/">CapMart</a>
      </li>
      <li><a href="https://a-myriad-of-strivings.netlify.app/">AMOS</a></li>
      <li>
        <a href="https://antiquarian-cup.netlify.app/">Sylvan Circle Academy</a>
      </li>
      <li>
        COMING SOON: Slacker Circle Home School (formerly
        <a href="https://codified-heart-song.netlify.app/"
          >Socratic Circle Home School</a
        >
        - UNDER RENOVATION)
      </li>
    </ul>
    <h3>For Layers AC, CBC, CGC, and Further</h3>
    <ul>
      <li>
        <a href="https://github.com/BBuchholz/worthy-mountain"
          >Worthy Mountain Builders Template</a
        >
        - a standard, base template we are currently developing for all
        Builder's General Usage, see tha README for more details and checkout
        tha <a href="https://worthy-mountain.netlify.app/">live demo here</a>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
