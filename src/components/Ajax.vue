<template>
  <div>
      <button v-on:click='sendRequest'>Send request</button>
      <p>{{message}}</p>
  </div>
</template>

<script>
export default {
  data: () => ({
      message: ''
  }),

  methods:{
      async sendRequest() {
          const url = 'https://swapi.dev/api/people/1/'
          try{
              const response = await fetch(url)
              const data = await response.json()
              console.log(data)
              let person = JSON.parse(data)
               console.log(person)
                
              this.message = person          
          }
          catch(error){
              this.message = (error)
          }
      }
  }
}
</script>

<style scoped>

</style>