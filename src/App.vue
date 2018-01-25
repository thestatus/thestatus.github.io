<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="sass">
  @import 'spectre.css'

  .container
    max-width: 900px
    padding: 10px 5%
</style>
