<!--
VCRYPT by Alexander Abraham, a.k.a. "Angel Dollface".
Licensed under the MIT license.
-->

<template>
  <HeadingCog/>
  <CryptCog/>
  <FooterCog/>
</template>

<script>
import CryptCog from './components/CryptCog.vue';
import HeadingCog from './components/HeadingCog.vue';
import FooterCog from './components/FooterCog.vue';
export default {
  name: 'App',
  components: {
    CryptCog,
    HeadingCog,
    FooterCog,
  }
}
</script>

<style lang="scss">
@font-face {
  font-family: 'Cyberpunk';
  src: url('https://angeldollface.art/assets/fonts/Cyberpunk.ttf') format('truetype');
}
@font-face {
  font-family: 'Mono';
  src: url('https://angeldollface.art/assets/fonts/Mono.ttf') format('truetype');
}
@font-face {
  font-family: 'PSB';
  src: url('https://angeldollface.art/assets/fonts/PSB.ttf') format('truetype');
}
$hoverColor: #FF7BAC;
$headingFont: 'Cyberpunk';
$contentFont: 'Mono';
$buttonFont: 'PSB';
$accentColor: #000000;
$mainColor: #EA1573;
@import './sass/desktop.scss';
@import './sass/responsive.scss';
</style>
