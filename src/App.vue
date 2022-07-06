<template>
  <div id="app">
    <MyTitle title="La mia prima app con Vue CLI!"/>
    <MyHero img="https://scitechdaily.com/images/How-Japans-Snow-Monkeys-Cope-With-the-Cold.jpg"
      img_alt="snow-monkey"
      title="Hot Springs Help Japan’s Snow Monkeys Cope With The Cold"
      paragraph="Japanese macaques, also known as snow monkeys, have been enjoying regular baths in the hot spring at Jigokudani in Japan for decades – and have even become a popular tourist attraction."   
    />   
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
