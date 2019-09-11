<template lang="html">

</template>

<script>
import eventBus from '../main'

export default {
  name: 'list-component',
  props: ['country'],
  methods: {
    handleClick() {
      eventBus.$emit('country-selected', this.country)
    }
  }
}
</script>

<style lang="css" scoped>
</style>
