<template>
    <div>
     <h1>{{ msg2 }}</h1>
     <button @click="helloWorld"  >Click me!</button>
    </div>
</template>



<script>
export default {
    name: 'ToDoItem',
    props: {
    msg2: String,
  },
    methods: {
        helloWorld(){
            console.log("hello world")
        }
    }
};


</script>

<style>

</style>
