<template>
  <div class="container">
    <index1 class="item"></index1>
    <index2 class="item"></index2>
  </div>
</template>

<script lang=ts>
// *追記
import Vue from 'vue';
import index1 from '../components/index1.vue'
import index2 from '../components/index2.vue'

// *変更
export default Vue.extend ({
  components: {
    index1,
    index2
  }
})
</script>

<style>
.container {
  display: flex;
}
.item {
  margin: 10px;
  padding: 10px;
}
</style>
