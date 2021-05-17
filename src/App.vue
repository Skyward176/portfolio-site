<template>
  <v-app>
    <v-main>
      <Homepage/>
    </v-main>
  </v-app>
</template>

<script>
import Homepage from './components/Homepage.vue'

export default {
  name: 'App',

  components: {
    Homepage,
  },

  data: () => ({
    //
  }),
}
</script>
