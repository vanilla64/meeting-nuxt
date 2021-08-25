<template>
  <div class="header__content">
    <div class="header__column">
      <h1 class="header__title">The best video online meeting software.</h1>
      <p class="header__text">Many desktop publishing packages and web page editors now use Lorem Ipsum as their default</p>
      <button class="header__start-btn">Start for free</button>
    </div>
    <img class="header__img" src="/bg1.png" alt="Image">
    <img class="header__img_second" src="/bg2.png" alt="Image">
  </div>

</template>
<style lang="sass" scoped>
.header__content
  margin: 0 auto
  height: 518px
  width: $wrapperWidth
  position: relative
  @media screen and (max-width: $width1380)
    display: flex
    flex-direction: column
    align-items: center
    min-height: 650px
    @media screen and (max-width: $width660)
      max-height: 400px
    @media screen and (max-width: 500px)
      max-height: 100px
.header__column
  display: flex
  flex-direction: column
  justify-content: center
  max-width: 498px
  height: 100%
  @media screen and (max-width: $width1380)
    height: 341px
    justify-content: flex-start
    align-items: center
  @media screen and (max-width: $width660)
    height: 260px
  @media screen and (max-width: 380px)
    height: 290px
.header__title
  margin: 0 0 16px
  font-weight: 600
  font-size: 48px
  line-height: 60px
  color: $darkBlue
  @media screen and (max-width: $width1380)
    text-align: center
  @media screen and (max-width: $width660)
    font-size: 28px
    line-height: 27px
.header__text
  margin: 0 0 34px
  font-style: normal
  font-weight: normal
  font-size: 17px
  line-height: 28px
  color: $darkBlue
  @media screen and (max-width: $width1380)
    text-align: center
  @media screen and (max-width: $width660)
    font-size: 14px
    line-height: 20px
.header__start-btn
  width: 180px
  outline: none
  border: none
  border-radius: 6px
  padding: 23px 37px 22px 38px
  background: $lightGreen
  font-style: normal
  font-weight: 500
  font-size: 17px
  line-height: 21px
  color: $darkBlue
.header__img
  height: 518px
  object-fit: cover
  position: absolute
  top: 0
  right: 0
  @media screen and (max-width: $width1380)
    position: static
    max-width: 550px
    object-fit: cover
    object-position: right
  @media screen and (max-width: 630px)
    display: none
.header__img_second
  display: none
  @media screen and (max-width: 630px)
    width: 100%
    object-fit: contain
    display: block
</style>
