# Vue guide

<style>
  .main {
    color: #2c3e50;
  }
  .text {
    color: #4fc08d;
  }
</style>

<template>
  <div class="main">
    <h2> Hello <span class="text">{{ name }}</span>!</h2>
    <h2>Features</h2>
    <ul>
      <li v-for="text in features">{{ text }}</li>
    </ul>
  </div>
</template>

<script>
  module.exports = {
    data () {
      return {
        name: 'Vuep',
        features: [
          'Single File Component',
          'Babel for ES6/JSX/UMD/CommonJS',
          'Scoped style',
          'Customizable JavaScript scope'
        ]
      }
    }
  }
</script>