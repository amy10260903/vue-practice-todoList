<template>
    <div class="todo-footer">
        <label>
            <input type="checkbox">
        </label>
        <span>已完成2 / 全部3</span>
        <button class="btn btn-danger">Delete completed task</button>
    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
/* Footer */
.todo-footer {
    margin: 10px 30px;
    text-align: left;
}

.todo-footer button {
    float: right;

}
</style>