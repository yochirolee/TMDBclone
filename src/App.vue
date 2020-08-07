<template>
  <div id="app">
    <Header msg="Welcome to Your Vue.js App"/>
     <div class='container'>
    <Jumbotrom/>
    <MainSlider/>
     </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotrom from './components/Jumbotrom'
import MainSlider from './components/MainSlider'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotrom,
    MainSlider
  }
}
</script>

<style>

html {
    font-family: sans-serif; /* 1 */
    -ms-text-size-adjust: 100%; /* 2 */
    -webkit-text-size-adjust: 100%; /* 2 */
    --lightGrey: 227,227,227;
    --tmdbDarkBlue: 3,37,65;
    --tmdbLightBlue: 1,180,228;
    --tmdbLighterGreen: 192,254,207;
    --tmdbLightGreen: 30,213,169;
    --tmdbLogoGreen: 144,206,161;
    --tmdbLogoOrange: 253,193,112;
    --tmdbLogoRed: 217,59,99;
    --accountSilver: 149,149,149;
    --accountPink: 234,20,140;
    --accountPurple: 128,91,231;
    --accountGreen: 1,210,119;
    --accountTeal: 1,198,172;
    --accountLightBlue: 1,180,228;
    --accountBlue: 1,119,210;
    --accountOrange: 210,119,1;
    --accountYellow: 210,144,1;
    --accountRed: 212,2,66;
    --imageBorderRadius: 8px;
  }
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: "Source Sans Pro", Arial, sans-serif;
  font-size: 1em;
}
.container{
 margin:0px 4.5rem;
}

</style>
