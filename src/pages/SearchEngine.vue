<template>
  <div class="container">
    <a>{{ user }}</a>
  </div>
</template>

<script>
  export default{
    setup(){
      const user = "berkeley"
      const text = ""
      console.log("seetup");
      return {
        user
      }
    },
    created(){
      console.log("created");
    },
    data(){

    },
    methods: {

    }
  }
</script>
