<template>
  <header class="navbar">
    <div class="container">
      <section class="navbar-section">
        <a href="#" class="navbar-brand mr-2">
          <img src="../assets/logo.svg" class="img-fit-contain">
        </a>
        <a href="#" class="btn btn-link">Docs</a>
        <a href="https://github.com/thestatus/thestatus.github.io"
            class="btn btn-link"
            target="_blank">GitHub</a>
      </section>
    </div>
  </header>
</template>
<script>
export default {
  name: 'Header',
  data: () => ({

  })
}
</script>
<style lang="sass" scoped>
  .navbar
    border-bottom: 1px solid #ecf0f1
    background-color: #ffffff

  .navbar-brand
    img
      height: 30px
</style>
