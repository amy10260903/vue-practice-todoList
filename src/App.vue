<template>
  <div id="app">
    <div class="container">
      <Header/>
      <TodoList/>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header";
import TodoList from "@/components/TodoList";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Header,
    TodoList,
    Footer
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
    background-color: orangered;
  }
  input[type=checkbox]:checked {
    background: skyblue;
  }
</style>
