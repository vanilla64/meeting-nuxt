<template>
  <div class="companies">
    <ul class="companies__list">
      <li class="companies__list-item">
        <img src="/airbnb.png" alt="Airbnb logo">
      </li>
      <li class="companies__list-item">
        <img src="/hubspot.png" alt="Hubspot logo">
      </li>
      <li class="companies__list-item">
        <img src="/Google-Logo.png" alt="Google Logo">
      </li>
      <li class="companies__list-item">
        <img src="/Microsoft-Logo.png" alt="Microsoft Logo">
      </li>
      <li class="companies__list-item">
        <img src="/Walmart-Logo.png" alt="Walmart Logo">
      </li>
      <li class="companies__list-item">
        <img src="/FedEx-Logo.png" alt="FedEx Logo">
      </li>
    </ul>
  </div>
</template>
<style lang="sass" scoped>
.companies
  width: 100%
  &__list
    list-style-type: none
    margin: 0
    padding: 0
    display: grid
    grid-template-columns: repeat(6, 1fr)
    @media screen and (max-width: $width1120)
      grid-template-columns: repeat(4, 1fr)
  &__list-item
    text-align: center
    @media screen and (max-width: $width1120)
      img
        height: 16px
    @media screen and (max-width: $width1120)
      img
        height: 12px
    &:nth-child(5)
      @media screen and (max-width: $width1120)
        display: none
    &:nth-child(6)
      @media screen and (max-width: $width1120)
        display: none
</style>
