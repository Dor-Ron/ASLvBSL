<template lang="pug">
main
  v-container
    v-layout
      v-flex(xs10 sm8 md4 offset-xs1 offset-sm2 offset-md4)
        h2 ASL (Top) / BSL (Bottom)
  app-card(imgSrcs="[]")
</template>

<script>
import Card from './Card.vue'

export default {
  name: 'Home',
  components: {
    'app-card': Card
  }
}
</script>

<style scoped lang="stylus">

</style>
