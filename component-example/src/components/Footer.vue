<template>
    <footer>
        <p>{{ copyright }}</p>
    </footer>
</template>
<script>
export default {
    data(){
        return{
            copyright: 'Copyright @2021'
        }
    }
}
</script>
<style scoped>
footer{
    background: #222;
    padding: 6px;
}
p{
        color: red;
        text-align: left;
}
</style>
