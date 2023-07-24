<template>
  <div class="hello">
    <input type="text" v-model="form.name" />
    <input type="text" v-model="form.email" />
    <input type="text" v-model="form.pass" />
    <input type="text" v-model="form.confirmPass" />
    <button @click="submit">submit</button>
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
      showParagraph: false,
      i: 20,
      arr1:[1,2, 3,  4, 5, 6, 7, 8, 9],
      form:{
        name: '',
        email: '',
        pass: '',
        confirmPass: ''
      },
    }
  },
  computed: {

  },
  methods: {
    submit() {
      console.log(this.form);
    }
  },
  created() {

  },
  mounted(){

  },
  updated() {
    console.log(this.inputValue)
  },
  unmounted() {
    
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  display:block;
}
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
