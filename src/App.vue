<template>
  <MyLinks />
  <img alt="Vue logo" src="./assets/Dealmaker.png" style="height:128px;width: 128px;">
  <HelloWorld msg="Hi hiii!" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyLinks from './components/Links.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyLinks
  }
}
</script>

<style>
#app {
  font-family: 'Mononoki Nerd Font';
  display: flex;
  flex-direction: column;
  margin-left: 5%;
  width: 90%;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  border: solid;
  border-radius: 15px;
  border-color: #000000;
  background-color: #f3eab0;
}


img {
  align-self: center;
  border: solid;
  border-radius: 15px;
  border-width: 2px;
  image-rendering: optimizeSpeed;
  /* STOP SMOOTHING, GIVE ME SPEED  */
  image-rendering: -moz-crisp-edges;
  /* Firefox                        */
  image-rendering: -o-crisp-edges;
  /* Opera                          */
  image-rendering: -webkit-optimize-contrast;
  /* Chrome (and eventually Safari) */
  image-rendering: pixelated;
  /* Universal support since 2021   */
  image-rendering: optimize-contrast;
  /* CSS3 Proposed                  */
  -ms-interpolation-mode: nearest-neighbor;
  /* IE8+                           */

}

/* Regular */
@font-face {
  font-family: 'Mononoki Nerd Font';
  src: "./assets/Mononoki/MononokiNerdFont-Regular.ttf')";
  font-weight: normal;
  font-style: normal;
}

/* Bold */
@font-face {
  font-family: 'Mononoki Nerd Font';
  src: "./assets/Mononoki/MononokiNerdFont-Bold.ttf";
  font-weight: bold;
  font-style: normal;
}

/* Italic */
@font-face {
  font-family: 'Mononoki Nerd Font';
  src: "./assets/Mononoki/MononokiNerdFont-Italic.ttf')";
  font-weight: normal;
  font-style: italic;
}

/* Bold Italic */
@font-face {
  font-family: 'Mononoki Nerd Font';
  src: "./assets/Mononoki/MononokiNerdFont-BoldItalic.ttf";
  font-weight: bold;
  font-style: italic;
}
</style>
