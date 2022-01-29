<template>
  <div class="box">
    <div class="card-box">
      <Card></Card>
    </div>
    <div class="card-plus">
      <img class="svg-plus" src="./assets/plus.svg" alt="" />
    </div>
  </div>
</template>

<script>
import Card from './components/Card'
export default {
  name: 'Box',
  props: {
    //msg: String
  },
  components: {
    Card
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
