<script setup lang="ts">
import {  onMounted } from 'vue'
import { mountEditor } from '../build'
import '../build/dist/style.css'

onMounted(()=>{
  mountEditor('editor-root')
})

</script>

<template>
  <div id="editor-root"></div>
</template>

<style scoped>

</style>
