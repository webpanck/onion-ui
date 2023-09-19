<template>
  <div>
    Button 示例
  </div>
  <h1>示例</h1>
  <div>
    <Button>PCK</Button>
    <Button theme="button">PCK</Button>
    <Button theme="link">PCK</Button>
    <Button theme="text">PCK</Button>
  </div>
  <h1>示例2</h1>
  <div>
    <Button size="big">大大大</Button>
    <Button>普普通</Button>
    <Button size="small">小小小</Button>
  </div>
</template>

<script lang="ts">
import Button from '../lib/Button.vue'

export default {
  components: {Button}
}
</script>