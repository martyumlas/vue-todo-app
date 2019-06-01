<template>
    <div>
        <div v-for="(todo, index) in todos" :key="index">
            <TodoItem v-bind:todo="todo"/>
        </div>
    </div>
</template>

<script>
import TodoItem from './TodoItem.vue'
export default {
    components:{
        TodoItem
    },
    name: 'Todos',
    props:['todos']
    

}
</script>

<style>

</style>
