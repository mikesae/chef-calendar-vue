<template>
  <FullCalendar :config="config"/>
</template>

<script>
  import { FullCalendar } from 'vue-full-calendar'

  export default {
    name: 'Calendar',
    components: {
      FullCalendar
    },
    data () {
      return {
        config: {
          defaultView: 'month',
          header: {
            left: 'today',
            center: 'title',
            right: 'prev,next'
          }
        }
      }
    }
  }
</script>

<style>
  @import '../../node_modules/fullcalendar/dist/fullcalendar.css';
</style>
