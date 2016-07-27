<template>
  <div id="app">
  <graph-viewer></graph-viewer>
  </div>
</template>

<script>
import GraphViewer from './components/GraphViewer'

export default {
  components: {
    GraphViewer
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  position: absolute;
  background: black;
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100%;
  color: #efefef;
  font-family: Roboto,sans-serif;
}

h1, h2 {
  font-weight: normal;
}
</style>
