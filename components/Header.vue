<template>
  <header class="header">
    <AppBar />
    <HeaderContent />
  </header>
</template>

<style lang="sass" scoped>
.header
  margin: 0 0 134px
  padding: 35px 0 0
  box-sizing: border-box
  @media screen and (max-width: $width1120)
    margin: 0 0 50px
</style>


<script>
export default {
}
</script>
