<template>
  <div class="hello">
    <h1>Tha Book inTha GarDIN</h1>
    <div class="table">
      <ul>
        <li>Planning (uuid: e541bf15-67c8-4cb2-a0d3-c9e842f562c5)</li>
        <ul>
          <li>
            In the middle of the Garden, you see a book (have a prompt rewrite
            this, give me a good description of a book in the middle of the
            garden of eden)
          </li>
          <li>create a picture to illustrate it</li>
          <li>TOC style</li>
          <li>
            each site within [[anxious -grove]] should have a "Guilty Parties"
            page, the Peoples page wherein the portfolios and profiles of each
            "contributor" can be shared
          </li>
          <li>
            these should be mantles, and each one should have in their bio blurb
            a reference to some specific item that is their signature, and these
            should be available in CapMart to be able to play the role of that
            persona
          </li>
          <li>
            as we move towards the development of CupMart we can have their bios
            mention they are "retiring their reliance on" that previous item and
            joining the ranks of a "cup bearer" or what have you, it creates a
            narrative hook that allows the [[fiction suit]] mockup to hold the
            status of the current migration, ie. the bio will change when the
            new options are available
          </li>
          <li>
            we will not distinguish between personas, so as to encourage perusal
            of all the persona pages, this gets visitors looking at people's
            portfolios and profiles...
          </li>
        </ul>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "AboutLinks",
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
.table {
  display: table;
  margin: 0 auto;
}
ul {
  list-style: none;
  padding: 10px;
  margin: 10px;
}
ul li {
  margin: 10px;
  padding: 20px;
  max-width: 500px;
  background: lightgray;
}
a {
  color: #42b983;
}
</style>
