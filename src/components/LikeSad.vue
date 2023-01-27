<script setup>
import { ref } from "vue";
const like = ref(0);
const sad = ref(0);

function likeClick() {
  like.value++;
}
function sadClick() {
  sad.value++;
}
</script>

<template>
  <div>
    <button @click="likeClick()">
      ปุ่ม like{{ like }}
    </button>
    <button @click="sadClick()">
      ปุ่ม sad{{ sad }}
    </button>
  </div>
</template>
<style></style>
