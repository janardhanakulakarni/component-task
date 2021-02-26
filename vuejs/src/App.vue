<template>
    <div>
        <app-header></app-header>
        <app-ninjas v-bind:ninjas="ninjas"></app-ninjas>
        <app-footer></app-footer>
    </div>
</template>

<script>
// Imports
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import Ninjas from './components/Ninjas.vue';
export default {
    components: {
        'app-header': Header,
        'app-footer': Footer,
        'app-ninjas': Ninjas
    },
    data () {
        return {
          ninjas: [
              {name: 'instamoja', speciality: 'Full stack platform', show: false},
              {name: 'ixigo', speciality: 'india-mobile travel market', show: false},
              {name: 'Unacademy', speciality: 'Hiring', show: false},
              {name: 'Shuttl', speciality: 'Conditionals', show: false},
              {name: 'Haptik', speciality: 'Webpack', show: false},
              {name: 'Swiggy', speciality: 'Restaurants', show: false}
          ]
        }
    }
}
</script>

<style>
body{
    margin: 0;
    font-family: 'Nunito SemiBold';
    color: rgb(201, 149, 38);
    background-color: aquamarine;
    text-decoration-line: underline;
}
</style>
