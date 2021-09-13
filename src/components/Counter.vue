<template>
<div>
     <h1>{{counter}}</h1>
    <button v-on:click="add" >+</button>
    <button v-on:click="sub">-</button>
    <button v-on:click="reset" >10</button>
</div>
</template>

<script>
export default {
  data: () => ({
    counter: 10,
  }),

   methods:{
    add(){this.counter++},
    sub(){this.counter-= 1},
    reset(){this.counter = 10},
    }
}
</script>

<style>
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
  color: #7adfb1;
}
</style>