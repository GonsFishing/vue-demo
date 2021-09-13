<template>
  <div class="Main">
    <counter></counter>
    <invisible-text></invisible-text>
   
    <!-- <button v-show="hideButton" v-on:click="invisible" >now you don't</button>
    <button v-show="lightButton" v-on:click="isLightOn">lights On</button>
    <button v-show="darkButton" v-on:click="isLightOn">lights Off</button> -->

  </div>
</template>

<script>
import Counter from './Counter.vue'
import invisibleText from './InvisibleText.vue'

export default {
  components: {
    Counter,
    invisibleText
  },
  data: () => ({
    showButton: true,
    hideButton: false,
    lightButton: true,
    darkButton: false
  }),

  methods:{}
}
</script>

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
