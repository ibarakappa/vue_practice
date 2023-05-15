<script setup>
// 導入別支vue
import TopView from "./components/Top.vue";
import BottomView from "./components/Bottom.vue";
</script>

<template>
   <div class="container">
      <TopView />
      <BottomView />
   </div>
</template>

<style>
.container {
   height: 100%;
   width: 100%;
   display: flex;
   flex-direction: column;
   justify-content: space-between;
}
</style>
