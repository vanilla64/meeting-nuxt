<template>
  <div class="appbar">
    <div class="appbar__left-side">
      <Logo />
      <HeaderNav />
    </div>
    <div class="appbar__right-side">
      <button class="appbar__signin-btn">Sign in</button>
      <button class="appbar__download-btn">Download</button>
    </div>
    <div class="burger">
      <div class="burger__line-top"></div>
      <div class="burger__line-bottom"></div>
    </div>
  </div>
</template>
<script>
export default {
}
</script>

<style lang="sass" scoped>
.appbar
  margin: 0 0 50px
  display: flex
  justify-content: space-between
  align-items: center
  &__left-side
    display: flex
    justify-content: flex-start
    align-items: center
  &__right-side
    display: flex
    justify-content: flex-end
    align-items: center
    @media screen and (max-width: $width950)
      display: none
  &__signin-btn
    margin: 0
    padding: 0
    min-width: 58px
    outline: none
    border: none
    background: transparent
    font-weight: 500
    font-size: 18px
    line-height: 20px
    color: $darkBlue
  &__download-btn
    box-sizing: border-box
    margin: 0 0 0 45px
    padding: 16px 27px
    outline: none
    border: none
    background: $darkBlue
    border-radius: 6px
    font-style: normal
    font-weight: 500
    font-size: 17px
    line-height: 20px
    color: $white
  .burger
    cursor: pointer
    display: none
    @media screen and (max-width: $width950)
      display: flex
      flex-direction: column
      align-items: flex-end
    &__line-top
      width: 28px
      margin: 0 0 8px
      border: 2px solid $darkBlue
    &__line-bottom
      width: 20px
      border: 2px solid $darkBlue
</style>
