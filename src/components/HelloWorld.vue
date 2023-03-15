<template>
  <div class="test">
    小王，我好困hhhhh, 我准备开始摸鱼了
    <HeartFilled :style="{ color: 'hotpink' }" />
    <a-icon type="step-forward" />
  </div>
  <a-spin size="large" />
</template>

<script setup lang="ts">
import { defineComponent } from 'vue'
import { HeartFilled } from '@ant-design/icons-vue'
</script>

<style scoped="less">
.test {
  font-size: 80px;
}
</style>
