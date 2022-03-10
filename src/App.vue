<template>
  <div id="app">
    <h1>La mia prima app con Vue CLI!</h1>
    <JumboTron />
  </div>
</template>

<script>
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    JumboTron
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img{
  max-width: 100%;
  display: block;
}

body{
  background-color: #4e6f9e;
  padding: 10px;
  user-select: none;
}

#app{
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

h1{
  color: #FFA208;
  padding: 30px;
  font-size: 40px;
}
</style>
