<template>
    <div>
        组件A
    </div>
</template>

<script setup lang='ts'>
import { ref,reactive } from 'vue'
import { useAttrs } from 'vue';
let attrs = useAttrs()
console.log(attrs.title);

</script>
<style scoped lang='less'>

</style>