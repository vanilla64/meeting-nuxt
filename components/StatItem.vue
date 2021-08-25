<template>
  <div class="stat-item">
    <h3 class="stat-item__title">{{ title }}</h3>
    <div class="stat-item__rating">
      <img class="stat-item__rate-img" :src="icon" alt="Stat icon">
      <img class="stat-item__rate-img" :src="icon" alt="Stat icon">
      <img class="stat-item__rate-img" :src="icon" alt="Stat icon">
      <img class="stat-item__rate-img" :src="icon" alt="Stat icon">
      <img class="stat-item__rate-img" :src="icon" alt="Stat icon">
    </div>
    <p class="stat-item__text">{{ text }}</p>
  </div>
</template>
<script>
export default {
  props: {
    title: { type: String },
    text: { type: String },
    icon: { type: String }
  }
}
</script>
<style lang="sass" scoped>
.stat-item
  margin: 0 93px 0 0
  display: flex
  flex-direction: column
  align-items: flex-start
  @media screen and (max-width: $width1120)
    margin: 0 75px 0 0
  @media screen and (max-width: 340px)
    margin: 0 30px 0 0
  &:last-child
    margin: 0
  &__title
    margin: 0 0 10px
    font-style: normal
    font-weight: 600
    font-size: 60px
    line-height: 70px
    letter-spacing: -1px
    color: $darkBlue
    @media screen and (max-width: $width1120)
      font-size: 40px
      line-height: 50px
  &__rating
    margin: 0 0 12px
  &__rate-img
    @media screen and (max-width: $width1120)
      width: 12px
      height: 10px
  &__text
    margin: 0
    font-style: normal
    font-weight: normal
    font-size: 16px
    line-height: 28px
    color: $darkBlue
    @media screen and (max-width: $width1120)
      font-size: 12px
      line-height: 24px

</style>
