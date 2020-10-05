<template>
  <div id="app">
    <br />
    <b-avatar
      src="https://software.thaiware.com/upload_misc/software/2014_12/thumbnails/11958_1610261210436H_152956.png"
      size="15%"
    ></b-avatar>
    <HelloWorld id="text" msg="" />
    <music />

  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import music from "./components/music.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    music,
  },
};
</script>
<style>
#app {
justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-size: cover;
  background-image: url();
}
#text {
  color: rgb(0, 0, 0);
}
</style>
