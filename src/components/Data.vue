<template>
  <h2>Options - {{o_firstname}} </h2>
</template>

<script>
import { ref } from 'vue'

export default {
  name: 'Data',
  setup(){
    const c_firstname = ref('Clark')
    return{
      c_firstname
    }
  },
  data() {
    return{
      o_firstname : 'Bruce',
    }
  }
}
</script>

<style scoped>
</style>
