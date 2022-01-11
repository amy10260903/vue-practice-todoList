<template>
    <div class="todo-main">
        <ul>
            <Item/>
            <Item/>
            <Item/>
        </ul>
    </div>
</template>

<script>
import Item from "@/components/Item";

export default {
    name: "TodoList",
    components: {Item}
}
</script>

<style scoped>
/* Main */
.todo-main {
    margin: 20px 30px;
}

.todo-main ul {
    list-style: none;
    margin: 0px;
    padding: 0px;
    border: solid 1px gray;
    border-radius: 5px;
}
</style>