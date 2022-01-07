<template>
  <div id="app">
    <div class="container">
      <div class="todo-header">
          <input type="text" placeholder="Enter something..."/>
      </div>
      <div class="todo-main">
        <ul>
          <li>
            <input type="checkbox"/>
            <span>Sleep</span>
            <button class="btn btn-danger">Delete</button>
          </li>
          <li>
            <input type="checkbox"/>
            <span>Sleep</span>
            <button class="btn btn-danger">Delete</button>
          </li>
        </ul>
      </div>
      <div class="todo-footer">
        <input type="checkbox"/>
        <span>已完成2 / 全部3</span>
        <button class="btn btn-danger">Delete completed task</button>
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
  body, html {
    font-size: 14px;
    font-family: 'Noto Sans TC', 'Roboto', sans-serif;
  }
  /* Base */
  .container {
    padding: 20px;
    margin: 50px 220px;
    text-align: center;
    border: solid 1px gray;
    border-radius: 5px;
  }
  .btn {
    padding: 5px;
    border: none;
    border-radius: 5px;
  }
  .btn-danger {
    background-color: tomato;
    color: white;
  }
  .btn-danger:hover {
    background-color: indianred;
  }

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
  .todo-main li {
    padding: 5px;
    text-align: left;
    border-bottom: solid 1px gray;
  }
  .todo-main li:last-child {
    border-bottom: none;
  }
  .todo-main li button {
    display: none;
    float: right;
  }
  .todo-main li:hover button {
    display: block;
  }

  /* Footer */
  .todo-footer {
    margin: 10px 30px;
    text-align: left;
  }
  .todo-footer button {
    float: right;

  }
</style>
