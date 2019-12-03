<template>
    <button class="task_delete" @click="deleteTask()">X</button>
</template>

<script>
export default {
  name: 'RemoveBtn',
  methods: {
    deleteTask() {
        this.$emit('deleteTask')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.task_delete {
  background: none;
  border: 0;
  border-radius: 50%;
  cursor: pointer;
  height: 24px;
  width: 24px;
}

.task_delete:hover {
  background-color: #ff6444;
  color: #fff;
}
</style>
