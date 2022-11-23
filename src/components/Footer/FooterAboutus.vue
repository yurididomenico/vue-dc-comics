<template>
    <div class="footer">
        <div class="contenitore65 flex-mode f-justify-between f-align-center">
            <a href="#" class="btn-signUp">SIGN-UP NOW!</a>
            <div class="section-followUs flex-mode f-align-center">
                <a href="#"><h2>FOLLOW US</h2></a>
                <a href="#"><img src="../../assets/img/footer-facebook.png" alt=""></a>
                <a href="#"><img src="../../assets/img/footer-twitter.png" alt=""></a>
                <a href="#"><img src="../../assets/img/footer-youtube.png" alt=""></a>
                <a href="#"><img src="../../assets/img/footer-pinterest.png" alt=""></a>
                <a href="#"><img src="../../assets/img/footer-periscope.png" alt=""></a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterAboutus'
    }
</script>

<style lang="scss" scoped>
    .footer
    {
        background-color: #303030;
        padding: 30px;
    }

    h2
    {
        color: #0087ff;
    }

    .btn-signUp
    {
        border: 2px solid #0087ff;
        padding: 15px;
        
        &:hover
        {
            background-color: black;
            color: #0087ff;
            font-weight: bold;
        }
        
    }

    .section-followUs
    {
        a
        {
            padding: 0 10px;
            h2:hover
            {
                color: rgb(226, 226, 226);
                text-shadow: 0 0 20px #0087ff;
            }

            img:hover
            {
                border-radius: 100%;
                background-color: white;
                box-shadow: 0 0 30px #0087ff;
            }
        }
    }
</style>