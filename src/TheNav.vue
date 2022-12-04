<template>
    <div class="d-flex">
        <img class="logo" src="/dc-logo.png" alt="">
        <ul class="nav nav-pills justify-content-center flex-grow-1">
            <li class="nav-item" v-for="button in navButtons">
                <a class="nav-link text-dark" href="#">{{button}}</a>
            </li>
            
        </ul>
        
    </div>
</template>


<script>
import { Button } from 'bootstrap';

export default {
    data () {
        return {
            navButtons: [
            "CHACACTHERS",
            "COMICS",
            "MOVIES",
            "TV",
            "GAMES",
            "COLLECTIBLES",
            "VIDEOS",
            "FANS",
            "NEWS",
            "SHOP"
            ]
        };
    },
    
};
</script>


<style scoped>
    .logo {
        width: 40px;
        height: 40px;
    }

    
</style>