<template>
  <div>
    <img id="img" width="300" height="300" src="./assets/雅棉_18.jpg" alt="">
  </div>
</template>

<script setup lang='ts'>
import { ref,reactive } from 'vue'
import useBase64 from './hooks'

useBase64({
  el: '#img'
}).then(res=>{
  console.log(res.baseUrl);
  
})

</script>
<style scoped lang='less'>

</style>