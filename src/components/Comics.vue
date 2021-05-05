<template>
   <div class="fumetto">
       <img :src="details.scr" :alt="details.series">
   </div>
</template>

<script>
export default {
name:'Comics',
props:['details'],
}
</script>

<style>

</style>