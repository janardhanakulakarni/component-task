<template>
    <header>
        <h1>{{ title }}</h1>
        <h4>(Click on the player name to get specification)</h4>
    </header>
</template>
<script>
export default {
    data(){
        return{
            title: 'Cricket-Players-Specifications'
        }
    }
}
</script>
<style scoped>
header{
    background: #d6a318;
    padding: 10px;
}
h1{
    color: #222;
    text-align: center;
}
h4{
  text-align:center;
  color:red;
}
</style>
