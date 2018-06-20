<template lang="pug">
v-card
  p pictureeess
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

</style>
