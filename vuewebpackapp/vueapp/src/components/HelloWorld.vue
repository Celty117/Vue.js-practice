<template>
  <div class="hello">
    <h1>Hello World</h1>
    <h2>Essential Links</h2>
    <h3>{{$route.params.worldmsg}}</h3>
    <hr>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  color: #42b983;
}
</style>
