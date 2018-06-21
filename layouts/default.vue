<template>
  <v-app>
    <v-content>
      <v-container grid-list-md>
        <v-layout row wrap>
          <v-flex md12>
            <logo/>
          </v-flex>
        </v-layout>
      </v-container>
      <v-container grid-list-md>
        <v-layout row wrap>
          <v-flex md8>
            <nuxt/>
          </v-flex>
          <v-flex md4>
            <right-menu/>
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
  import Logo from '~/components/Logo.vue'
  import RightMenu from '~/components/RightMenu'

  export default {
    components: {
      Logo,
      RightMenu
    }
  }
</script>

<style>


</style>
