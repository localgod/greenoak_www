<template>
  <div class="container">
    <h1>{{ title }}</h1>
    <p>Experiment in progress</p>
  </div>
</template>

<script setup>
const title = 'Greenoak';
</script>
<style>
body {
  margin: 0;
  padding: 0;
  background-color: #717a49;
}

.container {
  position: absolute;
  border: 2px solid #000000;
  left: 50%;
  width: 800px;
  margin-left: -400px;
  margin-top: -250px;
  top: 50%;
  height: 500px;
  background-color: #ffffff;
}
</style>
