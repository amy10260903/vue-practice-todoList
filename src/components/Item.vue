<template>
    <li>
        <label>
            <input type="checkbox">
            <span>Sleep</span>
        </label>
        <button class="btn btn-danger">Delete</button>
    </li>
</template>

<script>
export default {
    name: "Item"
}
</script>

<style scoped>
li {
    padding: 5px;
    text-align: left;
    border-bottom: solid 1px gray;
}

li:last-child {
    border-bottom: none;
}

li button {
    display: none;
    float: right;
}

li:hover button {
    display: block;
}
</style>