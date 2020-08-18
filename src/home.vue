<template>
  <div id="home">
    <h1>{{ msg }}</h1>
    <h2 v-bind:title="message">欢迎 </h2>
  </div>
</template>

<script>
export default {
  name: 'home',

  data () {
    return {
      msg: '1111111',
      message:'11222222'
    }
  }
}
</script>

<style scoped>

</style>
