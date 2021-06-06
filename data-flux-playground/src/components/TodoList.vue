<template>
    <ul>
        <tr>
            <td>Tâche 1</td>
            <td>
                <button>Marquer</button>
                <button>Supprimer</button>
            </td>
        </tr>
        <tr>
            <td>Tâche 2</td>
            <td>
                <button>Marquer</button>
                <button>Supprimer</button>
            </td>
        </tr>
        <tr>
            <td>Tâche 3</td>
            <td>
                <button>Marquer</button>
                <button>Supprimer</button>
            </td>
        </tr>
    </ul>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'TodoList',
  props: {
    msg: Array
  }
})
</script>
