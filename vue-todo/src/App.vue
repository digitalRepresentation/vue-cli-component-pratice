<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoInput></TodoInput>
    <TodoFooter></TodoFooter>
    <Todolist></Todolist>
  </div>
</template>


<script>
import TodoHeader from './components/TodoHeader.vue'
import TodoInput from './components/TodoInput.vue'
import TodoFooter from './components/TodoFooter.vue'
import TodoList from './components/TodoList.vue'

var my_cmp = {
  template: '<div>my component</div>'  
};

new Vue({
    el: '',
    components: {
      'my-cmp': my_cmp
    }
});

export default {
  components: {
    'TodoHeader' : TodoHeader,
    'TodoInput' : TodoInput,
    'TodoFooter' : TodoFooter,
    'TodoList': TodoList

  }
}
</script>

<style>

</style>
