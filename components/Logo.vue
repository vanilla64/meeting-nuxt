<template>
  <div class="logo">
    <img class="logo__img" src="/logo.svg" alt="Logo">
    <span class="logo__text">meeting</span>
  </div>
</template>
<style lang="sass" scoped>
.logo
  margin: 0 110px 0 0
  display: flex
  align-items: center
  @media screen and (max-width: $width1120)
    margin: 0 50px 0 0
  @media screen and (max-width: $width1024)
    margin: 0 50px 0 0

  &__img
    margin: 0 7px 0 0
    width: 32px
    height: 32px
    object-fit: contain
  &__text
    font-style: normal
    font-weight: 600
    font-size: 20px
    line-height: 20px
    color: $darkBlue
</style>
