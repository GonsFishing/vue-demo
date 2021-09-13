<template>
  <div>
   <button v-on:click="toggleText"> {{ textIsVisible ? 'hide ': 'show '}}text</button>
     
          toggleText(){this.textIsVisible = !this.textIsVisible},
    // invisible(){this.showButton = !this.showButton,
    // this.hideButton = !this.hideButton},

    // isLightOn(){this.lightButton = !this.lightButton,
    // this.darkButton = !this.darkButton},
    //   if (darkbutton) 
    //   { 
        
    //   }
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>