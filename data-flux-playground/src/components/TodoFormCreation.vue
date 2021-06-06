<template>
    <input id="add" type="text" placeholder="Nouvelle tâche">
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'TodoFormCreation',
  props: {
    msg: String
  }
})
</script>
