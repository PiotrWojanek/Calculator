<template>
  <Calculator />
</template>

<script>
import Calculator from './components/CalculatorSquare.vue'

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
body{
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin: 0;
  background-image:linear-gradient(rgb(0, 70, 70),rgb(0, 30, 30));
  padding: 0;
}
</style>
