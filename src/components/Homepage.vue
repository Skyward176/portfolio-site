<template>
    <v-app-bar
        absolute
        color="orange darken-2"
        dark
        shrink-on-scroll
        prominent
        scroll-target="#scrolling-techniques"
      >


        <v-btn
            text
            color='orange darken-1'
            size='x-large'
        >
            <v-text>Brandon Martinez</v-text>
        </v-btn>

        <v-btn text color='grey lighten-2'>
            <v-text>Home</v-text>
        </v-btn>

        <v-btn text color='grey lighten-2'>
            <v-text>Projects</v-text>
        </v-btn>

      </v-app-bar>
</template>
<script>
    export default {
        name: 'Homepage',
    }
</script>
