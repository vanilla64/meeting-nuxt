<template>
  <nav class="navigation">
    <ul class="navigation__list">
      <li class="navigation__list-item">Home</li>
      <li class="navigation__list-item">Feature</li>
      <li class="navigation__list-item">Pricing</li>
      <li class="navigation__list-item">Solution</li>
      <li class="navigation__list-item">Faq</li>
    </ul>
  </nav>
</template>
<style lang="sass" scoped>
.navigation
  width: 507px
  transition: .3s
  @media screen and (max-width: $width1024)
    width: 407px
  @media screen and (max-width: $width950)
    display: none
  &__list
    display: flex
    -webkit-justify-content: space-between
    list-style-type: none
    padding: 0
    margin: 0
  &__list-item
    font-style: normal
    font-weight: 500
    font-size: 18px
    line-height: 20px
    color: $darkBlue
</style>
