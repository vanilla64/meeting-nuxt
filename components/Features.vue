<template>
  <section class="features">
    <h2 class="features__title">Our Special Features</h2>
    <p class="features__subtitle">We are familiar with offline speed dating flow so we designed out online
      platform considering all the requirements
    </p>
    <ul class="features__list">
      <FeatureCard
        v-bind:img="'/pricing.svg'"
        v-bind:title="'Affordable Pricing'"
        v-bind:subtitle="'A dictionary of over 200 Latin words,with handful of model sentence. structures, to generate Lorem Ipsum'"
      />
      <FeatureCard
        v-bind:img="'/reliability.svg'"
        v-bind:title="'Affordable Pricing'"
        v-bind:subtitle="'A dictionary of over 200 Latin words,with handful of model sentence. structures, to generate Lorem Ipsum'"
      />
      <FeatureCard
        v-bind:img="'/secure.svg'"
        v-bind:title="'Affordable Pricing'"
        v-bind:subtitle="'A dictionary of over 200 Latin words,with handful of model sentence. structures, to generate Lorem Ipsum'"
      />
    </ul>
  </section>
</template>
<style lang="sass" scoped>
.features
  width: 100%
  &__title
    margin: 131px 0 12px
    text-align: center
    font-style: normal
    font-weight: 600
    font-size: 48px
    line-height: 64px
    letter-spacing: -1px
    color: $darkBlue
    @media screen and (max-width: $width660)
      margin: 51px 0 12px
      font-size: 24px
      line-height: 24px
  &__subtitle
    margin: 0 auto 48px
    max-width: 542px
    text-align: center
    font-style: normal
    font-weight: normal
    font-size: 16px
    line-height: 30px
    color: $darkBlue
    @media screen and (max-width: $width660)
      font-size: 14px
      line-height: 20px
  &__list
    display: flex
    list-style-type: none
    margin: 0
    padding: 0
    @media screen and (max-width: $width660)
      flex-direction: column
</style>
<script>
export default {
}
</script>
