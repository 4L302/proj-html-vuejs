<template>
    <div class="banner">
        <div class="container d-flex flex-row justify-content-between">
                <div class="logo">
                    <img src="../assets/img/avada-freelance-logo.png" alt="logo">
                </div>
                <div class="d-flex flex-row text-white buttons">
                    <a>
                        <i class="fa-solid fa-plus"></i>
                    </a>
                    <a>
                        <i class="fa-solid fa-bars"></i>
                    </a>
                </div>
            </div>
        <div class="title">
            <div class="d-flex flex-column justify-content-center align-items-center">
                <h3 class="text-uppercase">Avada Freelance</h3>
                <h1>Art Director</h1>
                <span class="text-uppercase">If it doesn't challenge you, it doesn't change you</span>
            </div>
        </div>
    </div>
</template>

<script>

import '../assets/style/variable.scss';

export default {
    name: 'headerComponent'
}
</script>

<style lang="scss" scoped>
.banner {
    background-image: url('../assets/img/banner_images.jpg');
    height: 100vh;
}

a {
    color: var(white);
    padding-top: 20px;
    padding-left: 10px;
}

.logo {
    height: 50px;
    padding-top: 20px;
}

i {
    font-size: xx-large;
}

h1{
    color: #fa225b;
    
}

h3, span{
    color: #ffffff;
}

.title{
    padding: 20%;
}

</style>