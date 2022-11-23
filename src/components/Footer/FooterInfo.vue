<template>
    <div class="sfondo-DC">
        <div class="contenitore65 padding-y-40 flex-mode">
            <div>
                <ul>
                    <li><h2>Titolo</h2></li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                </ul>
                <ul>
                    <li><h2>Titolo</h2></li>
                    <li>Testo</li>
                    <li>Testo</li>
                </ul>
            </div>

            <div>
                <ul>
                    <li><h2>Titolo</h2></li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                </ul>
            </div>

            <div>
                <ul>
                    <li><h2>Titolo</h2></li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
                    <li>Testo</li>
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