<template>
  <div>
    <v-card>
      <v-card-title primary-title>
        <h3 class="blue-grey--text">About me</h3>
      </v-card-title>
      <v-card-text class="blue-grey--text">
        <div class="about_me">
          <p>
          Hello, my name is Ivan. I work as a software developer in PT where I was born and raised.
        </p>
          <p>
            Currently working at Fuze INC. as a Custom Solution Developer for the UCaaS market.
        </p>
        <p>
          My interests ranges from software development, travel, gaming & sci-fi.
        </p>
        </div>
      </v-card-text>
    </v-card>

    <v-card class="margin_at_top">
      <v-card-title primary-title>
        <h3 class="blue-grey--text">Posts by Year</h3>
      </v-card-title>
      <v-card-text>
        <nuxt-link to="/2018">Posts of 2018</nuxt-link>
      </v-card-text>
      <v-card-text class="blue-grey--text">

      </v-card-text>
    </v-card>
  </div>
</template>

<script>
  import Index from '~/pages/index.vue'

  export default {
    components: {
      Index
    }
  }
</script>

<style>

.about_me {
  text-align: justify;
}

.margin_at_top {
  margin-top: 10px;
}

</style>
