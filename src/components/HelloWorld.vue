<template>
  <div class="hello">
    <h1>{{ message }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the jgcjgcjhckhjv,jvh
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  data() {
    return {
      message: 'This is mustache syntax',
      arr1: [],
      obj: {}
    }
  },
  computed: {

  },
  methods: {

  },
  created() {

  },
  mounted(){

  },
  updated() {
    
  },
  destroyed() {
    
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
