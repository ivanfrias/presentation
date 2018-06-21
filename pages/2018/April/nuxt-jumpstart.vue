<template>
  <div class="blue-grey--text">
    <h5>2018-04-29</h5>
    <h2>Nuxt.js jumpstart</h2>
    <br/>
    <div class="content">
      <p>After a couple of months with the old page lingering around,
        I've decided to revamp the whole thing. The previous version served
        more as a proof of concept, served specially to evaluate nuxt.js
        as a static site generator.</p>
    </div>

    <div class="content">
      <p>Nuxt is one of the many static site generator frameworks that exists
        which enable to develop a "structure" you can customize with your own
        style and functionality. Under the hood is powered by
        <a href="https://vuejs.org">Vue.js</a>. Like React, enables developers to
        create component-based applications that promote the reuse of software and
        decreate the need to import DOM-manipulating libraries like jQuery.
        There is a strong community supporting Vue.js and all related projects.
        The components being used come from <a href="https://vuetifyjs.com/en/">Vuetify</a>, the "stop-by"
        library for building material-design based interfaces.
      </p>
    </div>
  </div>
</template>

<script>
  export default {
  }
</script>

<style>
.content {
  text-align:justify;
}
</style>
