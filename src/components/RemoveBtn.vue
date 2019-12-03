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
</style>
