<template>
    <div>
        <div v-for="(todo, index) in todos" :key="index">
            <h3>{{todo.title}}</h3>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Todos',
    props:['todos']
    

}
</script>

<style>

</style>
