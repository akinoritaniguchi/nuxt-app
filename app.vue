<template>
  <div>
    <NuxtPage />
    
  </div>
</template>

<script>
 export default {
  data: function(){
    return{
      message: 'Hello world!'
    }
  },
  methods: {
    updateMassage(){
      this.message = 'Hello Nuxt3';
    }
  }
 }
</script>