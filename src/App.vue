<template>
  <WebViewer initialDoc="https://pdftron.s3.amazonaws.com/downloads/pl/demo-annotated.pdf"></WebViewer>
</template>

<script>
import WebViewer from './components/WebViewer.vue'

export default {
  name: 'App',
  components: {
    WebViewer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
