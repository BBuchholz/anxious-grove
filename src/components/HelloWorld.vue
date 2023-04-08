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
      <li>COMING SOON: Jacob's Salvage</li>
      <li>
        <a href="https://fearlessly-artifactual.netlify.app/">CapMart</a> (NEW!)
      </li>
      <li><a href="https://a-myriad-of-strivings.netlify.app/">AMOS</a></li>
      <li>
        <a href="https://antiquarian-cup.netlify.app/">Sylvan Circle Academy</a>
        (NEW!)
      </li>
      <li>
        COMING SOON: Slacker Circle Home School (formerly
        <a href="https://codified-heart-song.netlify.app/"
          >Socratic Circle Home School</a
        >
        - UNDER RENOVATION)
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
