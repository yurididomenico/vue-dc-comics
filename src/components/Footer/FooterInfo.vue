<template>
    <div class="sfondo-DC">
        <div class="contenitore65 padding-y-40 flex-mode f-justify-between p-relative">
            <div class="flex-mode">
                <div>
                    <ul>
                        <li><h2>DC COMICS</h2></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <ul>
                        <li><h2>SHOP</h2></li>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>

                <div>
                    <ul>
                        <li><h2>DC</h2></li>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talen Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Rating</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>

                <div>
                    <ul>
                        <li><h2>SITES</h2></li>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
            <img src="../../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterInfo'
    }
</script>

<style lang="scss" scoped>

// ----- GENERALE --------------------------------------------------------------- //
    .sfondo-DC
    {
        background-image: url('../../assets/img/footer-bg.jpg');
        overflow: hidden;
    }

    ul
    {
        margin: 20px;

        li:first-child
        {
            margin-bottom: 10px;
            color: white;
        }

        li
        {
            font-size: 0.7rem;
            color: grey;
            padding-bottom: 7px;
        }
    }

    img
    {
        width: 600px;
        aspect-ratio: 1/1;
        position: absolute;
        right: 0;
        top: -100px;

        
    }

    .p-relative
    {
        position: relative;
    }

    
</style>