<template>
    <nav class="banner d-flex">
        <img src="../assets/img/avada-freelance-logo.png" alt="logo">
        <div class="flex-end">
            <a>
                <i class="fa-solid fa-plus"></i>
            </a>
            <a>
                <i class="fa-solid fa-bars"></i>
            </a>
        </div>
        <div class="container d-flex justify-content-center ">
            
        </div>
    </nav>
</template>

<script>

import '../assets/style/variable.scss';

export default {
    name: 'headerComponent'
}
</script>

<style lang="scss">

.banner {
    background-image: url('../assets/img/banner_images.jpg');
}

a{
    color: $white;
}
</style>