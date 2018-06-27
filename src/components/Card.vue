<template lang="pug">
  v-container(fluid)
    v-layout
      v-flex(xs12 sm8 md4 offset-sm2 offset-md4)
        v-card.img-card
          v-card-media(src="http://www.supercoloring.com/sites/default/files/styles/coloring_medium/public/cif/2015/12/asl-sign-language-letter-a-coloring-page.jpg"
          height="180px"
          contain)
          hr
          v-card-media(src="https://www.yescoloring.com/images/A_british_sign_language_colouring_at_coloringkidsboys.gif"
          height="180px"
          contain)
</template>

<script>
export default {
  name: 'Card',
  props: {
    imgSrcs: {
      type: Array,
      required: true
    }
  }
}
</script>

<style scoped lang="stylus">
.img-card
  margin-top 20px
hr
  margin 10px auto
</style>
