<script setup lang="ts">
import { ref } from 'vue'
import { ElButton } from 'element-plus'
import 'element-plus/es/components/button/style/css'
const i = ref(0)
</script>

<template>
  <h1>Hello World</h1>
  <el-button @click="i++">Incrase: {{ i }}</el-button>
</template>
