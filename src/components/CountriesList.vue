<template lang="html">

</template>

<script>
import ListComponent from './ListComponent'

export default {
  name: 'countries-list',
  props: ['countries'],
  components: {
    "list-component": ListComponent
  }
}
</script>

<style lang="css" scoped>
</style>
