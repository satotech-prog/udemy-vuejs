<template>
<div>
  <p>いいね({{number}})</p>
<button @click="include">+1</button>
</div>

</template>

<script>
export default {
  data: function () {
    return {
      number: 5
    };
  },
methods: {
  include () {
    this.number += 1
    }
  }
};
</script>

<style>

</style>

