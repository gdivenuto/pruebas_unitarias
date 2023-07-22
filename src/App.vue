<script>
    import Counter from './components/Counter.vue'
    //import Indecision from './components/Indecision.vue'

    export default {
        name: 'App',
        components: {
            Counter
        }
    }
</script>

<template>
    <Counter :start="100" />
</template>

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
