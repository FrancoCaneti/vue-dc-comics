<template>
  <div class="fumetti">
    <img :src="details.thumb" :alt="details.series" />
  </div>
</template>

<script>
export default {
  name: "Comics",
  props: ["details"],
};
</script>

<style>
.fumetti {
  display: flex;
}
</style>