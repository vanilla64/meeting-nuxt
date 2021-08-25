<template>
  <section class="collaborate">
    <div class="collaborate__top-row">
      <h2 class="collaborate__title">Collaborate 2M+ startup
        and international companies
        ueses since 2018
      </h2>
      <div class="collaborate__statistic">
        <StatItem
          v-bind:icon="'/heart.svg'"
          v-bind:title="'15k'"
          v-bind:text="'Active Downloads'"
        />
        <StatItem
          v-bind:icon="'/star.svg'"
          v-bind:title="'4.9'"
          v-bind:text="'2,938 Rating'"
        />
      </div>
    </div>
    <Companies />
  </section>
</template>

<style lang="sass" scoped>
.collaborate
  width: 100%
  &__top-row
    margin: 0 0 50px
    display: flex
    justify-content: space-between
    @media screen and (max-width: $width1120)
      flex-direction: column
      margin: 0 0 26px
  &__title
    margin: 0
    max-width: 494px
    font-style: normal
    font-weight: 600
    font-size: 36px
    line-height: 50px
    color: $darkBlue
    @media screen and (max-width: $width1120)
      margin: 0 0 22px
      font-size: 20px
      line-height: 30px
  &__statistic
    display: flex
    @media screen and (max-width: $width1120)
      justify-content: center
</style>
<script>
export default {
}
</script>
