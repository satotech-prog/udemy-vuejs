<template>
  <div>
    <button @click="show = ! show">切り替え</button>
    <p v-if="show">hello</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show: true
    };
  }
};
</script>

<style >

</style>