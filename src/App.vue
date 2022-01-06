<template>
  <div id="app">
    <div class="container">
      <div class="todo-main">
        <div class="todo-header">
          <input type="text" placeholder="Enter something..."/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
  /* Base */
  .container {
    width: 100%;
    height: 100%;
  }
  .todo-main {
    margin: 50px 220px;
    text-align: center;
  }

  /* Header */
  .todo-header {
    width: 100%;
  }
  .todo-header input {
    width: 100%;
    height: 26px;
  }
</style>
