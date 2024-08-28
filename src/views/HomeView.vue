<template>
  <div class="home">
    <VueTypewriterEffect :strings="['hello', 'world']" />
  </div>
</template>

<script>
import VueTypewriterEffect from "vue-typewriter-effect";

export default {
  name: 'HomeView',
  data() {
    return {
    }
  },
  components: {
    VueTypewriterEffect
  }
}
</script>


<style>

</style>