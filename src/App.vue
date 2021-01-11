<template>
  <div>
    <LikeHeader></LikeHeader>
    <h2>{{number}}</h2>
    <LikeNumber></LikeNumber>
  </div>
</template>

<script scoped>
import LikeHeader from "./components/LikeHeader.vue";


export default {
  data() {
      return {
        number: 10
      }
  },

  components: {
    LikeHeader: LikeHeader
  }
}

</script>

<style scoped>
div {
  border: 1px solid blue;
}
</style>




