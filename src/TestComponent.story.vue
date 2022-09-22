<script lang="ts">
import { defineComponent } from 'vue'
import TestComponent from './TestComponent.vue'

export default defineComponent({
  components: {
    TestComponent
  }
})
</script>

<template>
  <Story>
    <TestComponent />
  </Story>
</template>
