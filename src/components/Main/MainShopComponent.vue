<template>
    <div class="bg-azzurro">
        <div class="contenitore65 padding-y-40">
            <ul class="flex-mode f-justify-around f-align-center">
                <li><a href="#" class="flex-mode f-align-center"><img src="../../assets/img/buy-comics-digital-comics.png" alt="Icona Digital Comics"><span>DIGITAL COMICS</span></a></li>
                <li><a href="#" class="flex-mode f-align-center"><img src="../../assets/img/buy-comics-merchandise.png" alt="Icona Digital Comics"><span>DC MERCHANDISE</span></a></li>
                <li><a href="#" class="flex-mode f-align-center"><img src="../../assets/img/buy-comics-subscriptions.png" alt="Icona Digital Comics"><span>SUBSCRIPTION</span></a></li>
                <li><a href="#" class="flex-mode f-align-center"><img src="../../assets/img/buy-comics-shop-locator.png" alt="Icona Digital Comics" class="width-"><span>COMIC SHOP LOCATOR</span></a></li>
                <li><a href="#" class="flex-mode f-align-center"><img src="../../assets/img/buy-dc-power-visa.svg" alt="Icona Digital Comics"><span>SC POWER VISA</span></a></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default
    {
        name: 'MainShopComponent'
    }
</script>

<style lang="scss" scoped>

    // ----- GENERALE --------------------------------------------------------------- //
    .bg-azzurro
    {
        background-color: #0282f9;
    }

    ul
    {
        li
        {
            span
            {
                padding: 0 15px;
            }

            img
            {
                width: 40px;
            }

            .width-
            {
                width: 30px;
            }
            
        }
    }
</style>