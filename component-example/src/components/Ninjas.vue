<template>
    <div id="ninjas">
        <ul>
            <li v-for="ninja in ninjas" v-on:click="ninja.show = !ninja.show">
                <h2>{{ ninja.name }}</h2>
                <h2 v-show="ninja.show">{{ ninja.score }}</h2>
                <h3 v-show="ninja.show">{{ ninja.speciality }}</h3>
            </li>
        </ul>
    </div>
</template>
<script>
export default {
    data(){
        return{
            ninjas: [
                {name: 'Sachin', speciality: 'Right-Hand Batsman', score: 'Runs: 18426', show: false},
                {name: 'Zahir Khan', speciality: 'Fast Bowler', score: 'Total wickets: 282', show: false},
                {name: 'Rahul-Dravid', speciality: 'Wall of Indaia', score: 'Runs: 13288', show: false},
                {name: 'M.S.Dhoni', speciality: 'Wc-Captain', score: 'Runs: 4876',show: false},
                {name: 'Virat Kohli', speciality: 'Run machine', score: 'Runs: 7463',show: false},
                {name: 'Jasprit Bumrha', speciality: 'Death over specialist', score: 'Total wickets: 108', show: false}
            ]
        }
    }
}
</script>
<style scoped>
#ninjas{
    width: 100%;
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
    box-sizing: border-box;
}
ul{
    display: flex;
    flex-wrap: wrap;
    list-style-type: none;
    padding: 0;
}
li{
    flex-grow: 1;
    flex-basis: 300px;
    text-align: center;
    padding: 30px;
    border: 1px solid #222;
    margin: 10px;
}
</style>
