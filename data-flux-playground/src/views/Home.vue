<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    <HeaderBar/>
    <TodoFormCreation/>
    <TodoList/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HeaderBar from '@/components/HeaderBar.vue'
import TodoFormCreation from '@/components/TodoFormCreation.vue'
import TodoList from '@/components/TodoList.vue'

export default defineComponent({
  name: 'Home',
  components: {
    HeaderBar,
    TodoFormCreation,
    TodoList
  }
})
</script>
