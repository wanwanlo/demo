<template>
  <div class="hello">
    {{msg}}{{age}}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      age:18
    }
  }
}
</script>


<style scoped>

</style>
