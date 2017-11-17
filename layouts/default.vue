<template>
  <div class="container">
    <div class="menu">
      <logo/>
	  <div class="content">
	    <nuxt/>
	  </div>
    </div>
  </div>
</template>

<script>
  import Logo from '~/components/Logo.vue'

  export default {
    components: {
      Logo
    }
  }
</script>

<style>

@font-face {
    font-family: 'Open Sans Condensed';
    src: url('~/assets/OpenSansCondensed-Light.ttf');
}

@font-face {
	font-family: 'Amatic SC';
	src: url('~/assets/AmaticSC-Regular.ttf');
}

body {
  background: url('~/assets/brick.png') no-repeat fixed center;
  background-size: 100% 100%;

  font-family: 'Open Sans Condensed', sans-serif;
  font-size: 13px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.container {
  display: flex;
  justify-content: center;
}

.menu {
  width: 500px;
}

</style>