<template>
  <div id="app">
    <section class="section">
      <h1 class="title">Am I Being Raptured?</h1>
      <div class="container is-fluid">
        <Rapture />
      </div>
      <div class="footer">
      </div>
    </section>
  </div>
</template>

<script>
import Rapture from './views/Rapture'

export default {
  components: {
    Rapture
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
