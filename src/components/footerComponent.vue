<template>
    <footer>
        <div class="container pt-5">
            <div class="d-flex flex-column justify-content-center align-items-center">
                <img src="../assets/img/avada-footer-logo.png" alt="logo">
                <div class="d-inline pt-3">
                    <a href="#">
                        <span>Copyright 2012-2020</span>
                    </a>
                    <span> | </span>
                    <a href="#">
                        <span>Avada Theme by <span class="text-white"> Theme Fusion</span></span>
                    </a>
                    <span> | </span>
                    <a href="#">
                        <span>All Rights Reserved</span>
                    </a>
                    <span> | </span>
                    <a href="#">
                        <span>Power by WordPress</span>
                    </a>
                </div>
                <!-- <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i> -->
            </div>
        </div>
    </footer>
</template>

<script>
export default{
    name: 'footerComponent'
}
</script>

<style lang="scss" scoped>
footer {
    background-color: #1d2028;
}

a{
    text-decoration: none;
    color: #7a89ab;
    font-size: small;
}
span{
    color: #7a89ab;
}

</style>