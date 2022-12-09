<script setup>
import CablesPatch from './components/CablesPatch.vue'
</script>

<template>
  <CablesPatch/>
  <CablesPatch patchDir="/patch2/" canvasId="othercanvas" :patchOptions="{ glCanvasResizeToWindow: false }"/>
</template>

<style scoped>
body {
  margin: 0;
  background-color: #000;
  color: #fff;
  font-family: Helvetica, Arial, sans-serif;
  overflow: hidden; /* disable scrolling / rubberband effect on mobile */
}

canvas {
  display: block;
  position: absolute;
  outline:0;
}

* {
  /* disable on touch highlights of html elements, especially on mobile! */
  -webkit-tap-highlight-color: transparent;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

</style>
