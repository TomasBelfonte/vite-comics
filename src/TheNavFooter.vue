<template>
    <div class="container justify-content-center space-between">
        <div class="d-flex py-3 ">
            <div class="py-5 container d-flex gap-5 align-items-center space-between" >
                <button class="tb-button text-light">SIGN-UP NOW</button>
                <div>
                    <img class="image ms-5" src="/" alt="">
                    <p class="text-primary">FOLLOW US</p>
                </div>
                <div>
                    <img class="image" src="/footer-facebook.png" alt="">
                
                </div>
                <div>
                    <img class="image" src="/footer-twitter.png" alt="">
                
                </div>
                <div>
                    <img class="image" src="/footer-youtube.png" alt="">
                
                </div>
                <div>
                    <img class="image visa" src="/footer-pinterest.png" alt="">
                
                </div>
                <div>
                    <img class="image visa" src="/footer-periscope.png" alt="">
                
                </div>
            </div>
        
        </div>
    </div>
    
</template>


<script>
import { Button } from 'bootstrap';

export default {
    data () {
        return {
        };
    },
    
    
};
</script>


<style scoped>
    .tb-button {
        border: 1px solid blue;
        font-size: 15px;
        padding: 10px;
        color: white;
        background-color: #333333;
    }

    .image {
        height: 40px;

    }
</style>