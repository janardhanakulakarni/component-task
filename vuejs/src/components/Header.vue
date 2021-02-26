<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>
<script>
export default {
    data(){
        return{
            title: 'The-10 startups in india'
        }
    }
}
</script>
<style scoped>
header{
    background: lightgreen;
    padding: 10px;
}
h1{
    color: rgb(197, 34, 34);
    text-align: center;
}
</style>