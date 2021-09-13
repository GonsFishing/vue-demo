<template>
  <div class="Main">
    <counter></counter>
    <invisible-text></invisible-text>
    <light-button></light-button>
   
    <!-- <button v-show="hideButton" v-on:click="invisible" >now you don't</button>
    <button v-show="lightButton" v-on:click="isLightOn">lights On</button>
    <button v-show="darkButton" v-on:click="isLightOn">lights Off</button> -->

  </div>
</template>

<script>
import Counter from './Counter.vue'
import InvisibleText from './InvisibleText.vue'
import LightButton from './LightButton.vue'

export default {
  components: {
    Counter,
    InvisibleText,
    LightButton
  },
  data: () => ({
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
