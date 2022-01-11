<template>
    <div class="todo-header">
        <input type="text" placeholder="Enter something..."/>
    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
/* Header */
.todo-header {
    margin: 10px 30px;
    padding-right: 10px;
}

.todo-header input {
    width: 100%;
    height: 26px;
    border: solid 1px gray;
    border-radius: 5px;
    padding: 5px;
}
</style>