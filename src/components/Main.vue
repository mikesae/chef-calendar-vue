<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Calendar/>
  </div>
</template>

<script>

  import Calendar from './Calendar'

  export default {
    name: 'Main',
    components: {
      Calendar
    },
    data () {
      return {
        msg: 'Chef'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  a {
    color: #42b983;
  }
</style>
