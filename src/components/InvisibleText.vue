<template>
  <div>
    <button v-on:click="toggleText"> {{ textIsVisible ? 'hide ': 'show '}}text</button>
    <span v-show="textIsVisible"> Now you see me </span>
  </div>
</template>

<script>
export default {
  data: () => ({
    textIsVisible: true,
  }),
  methods:{
    toggleText(){this.textIsVisible = !this.textIsVisible},
  }
}
</script>

<style>

</style>