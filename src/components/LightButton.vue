<template>
  <div>
   <button v-bind:class="{black: !isLightOn}" v-on:click="toggleLight"> Light switch</button>
  </div>
</template>

<script>
export default {
  data:() => ({
      isLightOn: true
  }),

  methods:{
    toggleLight(){this.isLightOn  = !this.isLightOn
    }
  }
}
</script>

<style>
.black{
    background-color:#2d2d2e
}
</style>