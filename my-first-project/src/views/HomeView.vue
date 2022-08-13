<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <ToDoItem msg2="Hola"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import ToDoItem from '@/components/ToDoItem.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ToDoItem,
  },
};
</script>
