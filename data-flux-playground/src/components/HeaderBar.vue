<template>
    <h1>Ma liste de tâches</h1>

    <button>Supprimer les tâches terminées</button>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HeaderBar',
  props: {
    msg: String
  }
})
</script>
