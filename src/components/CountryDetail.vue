<template lang="html">
<main v-if="country">
  <p>{{country.name}}</p>
  <p>{{country.capital}}</p>
  <p>{{country.population}}</p>
</main>
</template>

<script>
export default {
  name: 'country-detail',
  props: ['country']
}
</script>

<style lang="css" scoped>
</style>
