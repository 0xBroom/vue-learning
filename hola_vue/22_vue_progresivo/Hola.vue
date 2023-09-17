<template>
  <div>
    <p>Lorem ipsum dolor</p>
    <div>{{ text }}</div>
  </div>
</template>
 
<script>
export default {
  data() {
    return {
      text: 'Hello, world!'
    }
  }
}
</script>
 
<style>
p {
  color: red;
}
</style>