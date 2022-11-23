<template>
    <div class="sfondo-DC">
        <div class="contenitore65 padding-y-40 flex-mode">
            <div>
                <ul>
                    <li><h2>DC COMICS</h2></li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <li><h2>SHOP</h2></li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div>
                <ul>
                    <li><h2>DC</h2></li>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talen Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Rating</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>

            <div>
                <ul>
                    <li><h2>SITES</h2></li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>            
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

</style>