<template>
  <div>Wynik: {{ score }}</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    score: Number,
  },
})
</script>

<style lang="scss" scoped>
@import '@/styles/index.scss';

div {
  font-size: 25px;
  font-weight: 600;
  margin-bottom: 10px;
}
</style>
