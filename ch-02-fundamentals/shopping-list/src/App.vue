<template>
  <div id="app"  class="container">
  <h2>{{ title }}</h2>
    <add-item-component></add-item-component>
    <items-component></items-component>
    <div class="footer">
      <hr>
      <em>Change the title of your shopping list here</em>
      <change-title-component></change-title-component>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
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
