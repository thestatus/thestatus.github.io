<template>
  <div class="container">
    <Main/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>
    <Card/>

    <ul class="pagination">
  <li class="page-item disabled">
    <a href="#" tabindex="-1">Previous</a>
  </li>
  <li class="page-item active">
    <a href="#">1</a>
  </li>
  <li class="page-item">
    <a href="#">2</a>
  </li>
  <li class="page-item">
    <a href="#">3</a>
  </li>
  <li class="page-item">
    <span>...</span>
  </li>
  <li class="page-item">
    <a href="#">12</a>
  </li>
  <li class="page-item">
    <a href="#">Next</a>
  </li>
</ul>
  </div>
</template>

<script>
import Main from '@/components/Main'
import Card from '@/components/Card'

export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },

  components: {
    Main,
    Card
  }
}
</script>

<style scoped>

</style>
