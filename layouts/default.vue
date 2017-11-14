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
@import url('https://fonts.googleapis.com/css?family=Amatic+SC');
@import url('https://fonts.googleapis.com/css?family=Amatic+SC|Open+Sans+Condensed:300');

body {
  background: url('../static/brick.jpg') no-repeat fixed center;
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