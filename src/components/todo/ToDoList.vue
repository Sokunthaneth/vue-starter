<template>
  <div>
      <h1>To Do List</h1>
      <ToDoItem/>
  </div>
</template>

<script>
import ToDoItem from './ToDoItem';

export default {
    name: 'ToDoList',
    components: {
        ToDoItem,
    },
    props: {

    }
}
</script>

<style scoped>

</style>