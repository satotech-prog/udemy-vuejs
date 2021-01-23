<template>
  <div class="main">
    <button @click="show = ! show">切り替え</button>
    <transition name="fade">
       <p v-if="show">hello</p>
    </transition>
    <transition name="slide">
      <p v-if="show">bye</p>
    </transition>
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
.fade-enter {

}
.fade-enter-active {

}
.fade-enter-to {

}
.fade-leave {

}
.fade-leave-active {

}
.fade-leave-to {
  
}
</style>