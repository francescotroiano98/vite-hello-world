<template>

    <div>
      <h1>
        {{ message }}
      </h1>
      <Title/>
    </div>
    
  </template>
  
  <script>
    import Title from './Title.vue'
    export default{
        components:{
            Title
        },
      data(){
  
        return{
          message: 'La mia prima app con Vite!'
        }
  
      },
  
    }
  
    
  
  </script>
  
  <style>
  
  </style>
  