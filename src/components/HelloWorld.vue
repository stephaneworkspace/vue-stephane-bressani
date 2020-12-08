<template>
  <div class="hello">
    <h1>Stéphane Bressani homepage</h1>
    <p>
      Welcome to my homepage... and to all others
    </p>
    <h3>Ukulele helper for iOs</h3>
    <ul>
      <li>
        <a
          href="https://ukulele.stephane-bressani.ch/#"
          target="_blank"
          rel="noopener"
          >Ukulele Helper for iOs</a
        >
      </li>
    </ul>
    <h3>My music project</h3>
    <ul>
      <li>
        <a href="https://www.electryps.ch" target="_blank" rel="noopener"
          >electryps.ch</a
        >
      </li>
      <li>
        <a
          href="https://www.soundcloud.com/electryps"
          target="_blank"
          rel="noopener"
          >soundcloud.com/electryps</a
        >
      </li>
      <li>
        <a
          href="https://www.soundcloud.com/solar-empire"
          target="_blank"
          rel="noopener"
          >soundcloud.com/solar-empire</a
        >
      </li>
    </ul>
    <h3>Astrology theme</h3>
    <ul>
      <li>
        <a
          href="https://www.astrologie-traditionnelle.net"
          target="_blank"
          rel="noopener"
          >www.astrologie-traditionnelle.net</a
        >
      </li>
    </ul>
    <h3>Code</h3>
    <ul>
      <li>
        <a
          href="https://www.github.com/stephaneworkspace"
          target="_blank"
          rel="noopener"
          >My github page</a
        >
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String
  }
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
  color: #000033;
}
</style>
