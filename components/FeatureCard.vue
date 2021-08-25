<template>
  <li class="feature-card">
    <img class="feature-card__img" :src="img" :alt="title">
    <h3 class="feature-card__title">{{ title }}</h3>
    <p class="feature-card__subtitle">{{ subtitle }}</p>
    <button class="feature-card__button">Learn more</button>
  </li>
</template>
<script>
export default {
  props: {
    img: { type: String },
    title: { type: String },
    subtitle: { type: String }
  }
}
</script>
<style lang="sass" scoped>
.feature-card
  margin: 0 80px 0 0
  max-width: 320px
  &:last-child
    margin: 0
  @media screen and (max-width: $width660)
    margin: 0 0 48px
  &__img
    @media screen and (max-width: $width660)
      width: 48px
      height: 48px
      object-fit: contain
  &__title
    margin: 28px 0 14px
    font-style: normal
    font-weight: 600
    font-size: 24px
    line-height: 29px
    color: $darkBlue
    @media screen and (max-width: $width660)
      margin: 20px 0 12px
      font-size: 20px
      line-height: 24px
  &__subtitle
    margin: 0 0 30px
    font-style: normal
    font-weight: normal
    font-size: 16px
    line-height: 26px
    color: $darkBlue
    opacity: .6
    @media screen and (max-width: $width660)
      margin: 0 0 20px
      font-size: 14px
      line-height: 24px
  &__button
    outline: none
    border: none
    background: transparent
    cursor: pointer
    font-style: normal
    font-weight: 500
    font-size: 20px
    line-height: 16px
    color: $darkBlue

</style>
