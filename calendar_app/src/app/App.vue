<template>
  <div id="app">
    <CalendarWeek />
    <CalendarEntry />
  </div>
</template>

<script>
import CalendarWeek from './components/CalendarWeek.vue'
import CalendarEntry from './components/CalendarEntry.vue'

export default {
  name: 'App',
  components: {
    CalendarWeek,
    CalendarEntry
  }
}
</script>

<style lang="scss">
html, body {
  height: 100%;
}

#app {
  height: inherit;
  background: #6e6e6e;
  display: flex;
  flex-direction: column;
  align-items: center;
  -webkit-align-items: center;
  justify-content: center;
  -webkit-justify-content: center;
}




</style>
