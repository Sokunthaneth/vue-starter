<template>
  <div>
      <h1>To Do</h1>
      <ToDoList/>
  </div>
</template>

<script>
import ToDoList from './ToDoList';

export default {
    name: 'Todo',
    components: {
        ToDoList
    },
    props: {

    }
}
</script>

<style scoped>

</style>