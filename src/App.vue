<template>
  <div id="app">
    <h1>Type here...</h1>
    <Textss />
    <Suggestions />
    
  </div>
</template>

<script>
import Textss from './components/Textss.vue'
import Suggestions from './components/Suggestions.vue'
export default {
  name: 'App',
  components: {
    Textss,
    Suggestions
  }
}
</script>

<style>

</style>
