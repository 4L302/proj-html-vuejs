<template>
    <div class="container d-flex justify-content-center flex-column align-items-center pt-5">
        <h2>Let's Work Together</h2>
        <h6 class="pt-2">Tell me more about your project</h6>
        <p class="text-center pt-2">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Odit veritatis aliquam, aliquid a voluptatum,
            molestiae
            consectetur maiores voluptates id perspiciatis pariatur quis numquam corporis voluptas culpa, nesciunt modi
            sequi
            sed.
        </p>
        <section class="container align-items-center d-flex flex-column">
            <div class="mb-4">
                <input type="text" class="form-control" id="formControlName" placeholder="NAME*">
            </div>
            <div class="mb-4">
                <input type="email" class="form-control" id="formControlEmail" placeholder="EMAIL*">
            </div>
            <div class="mb-4">
                <input type="numbers" class="form-control" id="formControlPhone" placeholder="PHONE*">
            </div>
            <div class="btn">
                <button class="text-uppercase text-white">Let's Talk</button>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'formComponent'

}
</script>

<style lang="scss" scoped>
button{
    background-color: #fa225b;
    border: #fa225b;
    padding: 5px 65px;
}

</style>