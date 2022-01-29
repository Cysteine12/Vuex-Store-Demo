<template>
  <div id="container">
    <Box></Box>
    <Box></Box>
    <Box></Box>
  </div>
</template>

<script>
import Box from './components/Box.vue'

export default {
  name: 'App',
  components: {
    Box
  }
}
</script>

<style>
.container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

.box {
    margin: 10px;
    padding: 10px;
    display: flex; 
}

.card-box {
    margin: 5px;
    padding: 10px;
    border: 3px solid #eee;
    border-radius: 10px;
    width: 60%;
    max-width: 700px;
}

.card-plus {
    margin: 5px;
    padding: 15px;
    border-radius: 10px;
    display: inline-block;
    float: right;
    height: 50px;
    width: 50px;
    color: #000;
    background-color: #eee;
}

.svg-arrow {
    color: #000;
    font-size: 60px;
    background-color: #eee;
    height: 50px;
    width: 50px;
}

.svg-plus {
    color: #000;
    height: 100%;
    width: 100%;
    background-color: #eee;
}
</style>
