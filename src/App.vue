<template lang="pug">
  #app
    v-app
      v-content
        v-container
          v-layout
            v-flex(xs10 sm8 md6 offset-sm1 offset-sm2 offset-md3)
              h1 ASL vs. BSL Alphabets
        v-container
          v-layout(xs12)
            v-flex
              app-home

</template>

<script>
import Home from '@/components/Home.vue'

export default {
  components: {
    'app-home': Home
  }
}
</script>

<style lang="stylus">
@import '~vuetify/src/stylus/main'
@import url('https://fonts.googleapis.com/css?family=Comfortaa')

h1
  font-size 42px
  font-family 'Comfortaa', cursive
</style>
