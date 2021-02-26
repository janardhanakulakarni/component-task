<template>
    <footer>
        <p>{{ copyright }}</p>
    </footer>
</template>
<script>
export default {
    data(){
        return{
            copyright: 'Copyright 2021 Vue Pandas'
        }
    }
}
</script>
<style scoped>
footer{
    background: rgb(180, 31, 31);
    padding: 6px;
}
p{
        color: lightgreen;
        text-align: center;
}
</style>