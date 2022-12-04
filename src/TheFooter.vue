<template>
    <div class="container justify-content-center d-flex height">
        <div class="d-flex py-3 mt-5 me-5 direction-column col-sm-4">
            <ul class="">
                <li>
                    <a class="text-light text-decoration-none fw-bolt" href="#"><strong>DC COMICS</strong></a>
                </li>
                <li class="" v-for="first in dcComics">
                    <a class="text-secondary text-decoration-none" href="#">{{first}}</a>
                </li>            
            </ul>

            <ul class="">
                <li>
                    <a class="text-light text-decoration-none fw-bolt" href="#"><strong>SHOP</strong></a>
                </li>
                <li class="" v-for="second in shop">
                    <a class="text-secondary text-decoration-none" href="#">{{second}}</a>
                </li>            
            </ul>

            <ul class="">
                <li>
                    <a class="text-light text-decoration-none fw-bolt" href="#"><strong>DC</strong></a>
                </li>
                <li class="" v-for="tirth in dc">
                    <a class="text-secondary text-decoration-none" href="#">{{tirth}}</a>
                </li>            
            </ul>

            <ul class="">
                <li>
                    <a class="text-light text-decoration-none fw-bolt" href="#"><strong>SITES</strong></a>
                </li>
                <li class="" v-for="fourth in sites">
                    <a class="text-secondary text-decoration-none" href="#">{{fourth}}</a>
                </li>            
            </ul>        
        </div>

        <div class="flex-grow-1 ms-5">
            <img  class="dc-size" src="/dc-logo-bg.png" alt="">
        </div>
    </div>
    
</template>


<script>

export default {
    data () {
        return {
            dcComics: [
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Videos",
                "News",
            ],

            shop: [
                "Shop DC",
                "Shop DC Collectibles"
            ],

            dc: [
                "Term of Use",
                "Privacy policy (New)",
                "Ad Choises",
                "Advertising",
                "Jobs",
                "Subscriptions",
                "Talent Workshops",
                "CPSC Certificate",
                "Rating",
                "Shop Help",
                "Contact Us"
            ],

            sites: [
                "DC",
                "MAD Magazine",
                "DC Kinds",
                "DC Universe",
                "DC Power Visa"
            ]
        };
    },
    
};
</script>


<style scoped>
    .dc-size{
        width: 550px;
        margin-top: -90px;

    }

    .height {
        max-height: 400px;
        overflow: hidden;
    }

    .whidth {
        max-width: 100px;
    }
</style>