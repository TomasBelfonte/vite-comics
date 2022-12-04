<template>
    <div class="container justify-content-right">
        <div class="d-flex py-3 mt-5">
            <img class="logo ms-3" src="/dc-logo.png" alt="">
            <ul class="nav nav-pills justify-content-end flex-grow-1">
                <li class="nav-item" v-for="button in navButtons">
                    <a class="nav-link text-dark" href="#">{{button}}</a>
                </li>
                
            </ul>
            
        </div>
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
        width: 50px;
        height: 50px;
    }

</style>