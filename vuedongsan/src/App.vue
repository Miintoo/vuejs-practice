<template>
  <img alt="Vue logo" src="./assets/logo.png">

  <div>
    <h4>{{products[0]}}</h4>
    <p>70 만원</p>
  </div>
  <div>
    <h4>{{products[1]}}</h4>
    <p>50 만원</p>
  </div>
  <div>
    <h4>{{products[2]}}</h4>
    <p>50 만원</p>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      price1: 60,
      price2: 70,
      products: ['역삼동원룸', '천호동원룸', '경기동원룸']

    }
  },
  components: {
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
