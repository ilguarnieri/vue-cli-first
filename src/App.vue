<template>
  <div id="app">
    <MyTitle />
    <MyHero />
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  background-color: #4e6f9e;
  user-select: none;
  padding: 10px;
}

#app{
  text-align: center;
}
</style>
