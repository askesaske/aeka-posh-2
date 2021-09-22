<template>
  <div>
<!--    <Header />-->
    <Nuxt />
    <Footer />
  </div>
</template>

<style lang="scss">
@import '../node_modules/swiper/swiper-bundle.css';
@import "../assets/scss/style";

@font-face {
  font-family: 'PlayfairDisplaySC';
  src: url('../assets/fonts/PlayfairDisplaySC-Bold.woff2') format('woff2'),
  url('../assets/fonts/PlayfairDisplaySC-Bold.woff') format('woff'),
  url('../assets/fonts/PlayfairDisplaySC-Bold.ttf') format('truetype');
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: 'PlayfairDisplaySC';
  src: url('../assets/fonts/PlayfairDisplaySC-Regular.woff2') format('woff2'),
  url('../assets/fonts/PlayfairDisplaySC-Regular.woff') format('woff'),
  url('../assets/fonts/PlayfairDisplaySC-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: 'Georgia';
  src: local('Georgia Regular'), local('Georgia-Regular'),
  url('../assets/fonts/Georgia.woff2') format('woff2'),
  url('../assets/fonts/Georgia.woff') format('woff'),
  url('../assets/fonts/Georgia.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: 'Georgia';
  src: local('Georgia Bold'), local('Georgia-Bold'),
  url('../assets/fonts/Georgia-Bold.woff2') format('woff2'),
  url('../assets/fonts/Georgia-Bold.woff') format('woff'),
  url('../assets/fonts/Georgia-Bold.ttf') format('truetype');
  font-weight: 700;
  font-style: normal;
}
</style>
