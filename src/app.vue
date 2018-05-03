<template>
  <div id="root">
    <comp-one></comp-one>
  </div>
</template>

<script>
import Display from './practice/csspractice/display.vue'

export default {
  components: {
    CompOne: Display
  },
  data () {
    return {
      text: 'Brad'
    }
  }
}
</script>

<style>
</style>
