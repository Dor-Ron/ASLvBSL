<template lang="pug">
  #app
    v-app
      v-content
        v-container
          v-layout(xs12)
            v-flex
              h1 ASL vs. BSL Alphabets
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
</style>
