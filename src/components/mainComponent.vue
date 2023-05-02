<template>
    <section id="aboutMe">
        <div class="container">
            <div class="d-flex flex-column justify-content-center align-items-center pt-4">
                <h2>About Me</h2>
                <span class="text-uppercase small">Ui & Ux Expert</span>
                <hr>
                <div class="row pt-2">
                    <div class="col-6 px-5 pb-3">
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, deleniti nemo quae tenetur
                            distinctio
                            inventore vitae in corporis doloremque sed veritatis reprehenderit molestias cumque qui ullam
                            voluptatem
                            explicabo sequi nobis?
                        </p>
                    </div>
                    <div class="col-6 px-5 pb-3">
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quos nemo eius dolores,
                            mollitia
                            autem facilis commodi. Consequuntur quisquam est rerum. Facere pariatur quisquam quis molestiae,
                            explicabo
                            veritatis repellat maiores.
                        </p>
                    </div>
                    <div class="col-6 px-5 pb-3">
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quos nemo eius dolores,
                            mollitia
                            autem facilis commodi. Consequuntur quisquam est rerum. Facere pariatur quisquam quis molestiae,
                            explicabo
                            veritatis repellat maiores.
                        </p>
                    </div>
                    <div class="col-6 px-5 pb-3">
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quos nemo eius dolores,
                            mollitia
                            autem facilis commodi. Consequuntur quisquam est rerum. Facere pariatur quisquam quis molestiae,
                            explicabo
                            veritatis repellat maiores.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="whyWorkWithMe">
        <div class="container">
            <div class="d-flex flex-column justify-content-center align-items-center pt-4">
                <h2>Why Work With Me</h2>
                <span class="text-uppercase small">Web - Branding - Ux/Ui</span>
                <hr>
                <div class="px-5 pb-3 text-center">
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, deleniti nemo quae tenetur distinctio
                        inventore vitae in corporis doloremque sed veritatis reprehenderit molestias cumque qui ullam
                        voluptatem
                        explicabo sequi nobis?
                    </p>
                </div>
                <div class="row">
                    <div class="col-4 px-3">
                        <i class="fa-solid fa-terminal fa-2xl"></i>
                        <h5 class="text-uppercase text-white small">Web Design</h5>
                    </div>
                    <div class="col-4 px-3">
                        <i class="fa-solid fa-shield-halved fa-2xl"></i>
                        <h5 class="text-uppercase text-white small">Branding</h5>
                    </div>
                    <div class="col-4 px-3">
                        <i class="fa-regular fa-gem fa-2xl"></i>
                        <h5 class="text-uppercase text-white small">Ui/Ux</h5>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="recentWork">
        <div class="container">
            <div class="d-flex flex-column justify-content-center align-items-center pt-4">
                <h2>Recent Work</h2>
                <span class="text-uppercase small">Web - Branding - Ux/Ui</span>
                <hr>
            </div>
        </div>
        <div class="row">
            <div class="col-6">
                <img src="../assets/img/portfolio1_featured_item.jpg" alt="">
            </div>
            <div class="col-6">
                <img src="../assets/img/portfolio2_featured_item.jpg" alt="">
            </div>
            <div class="col-6">
                <img src="../assets/img/portfolio3_featured_item.jpg" alt="">
            </div>
            <div class="col-6">
                <img src="../assets/img/portfolio4_featured_item.jpg" alt="">
            </div>
            <div class="col-6">
                <img src="../assets/img/portfolio5_featured_item.jpg" alt="">
            </div>
            <div class="col-6">
                <img src="../assets/img/portfolio6_featured_item.jpg" alt="">
            </div>
        </div>
    </section>
    <section id="viewWork">
        <div class="container">
            <div class="d-flex justify-content-center align-items-center p-4">
                <a>
                    <span class="text-white text-uppercase small">View All Work</span>
                </a>
            </div>
        </div>
    </section>


    <formComponent />
</template>

<script>
import formComponent from './formComponent.vue';


export default {
    name: 'mainComponent',
    components: {
        formComponent,
    },
}
</script>

<style lang="scss" scoped>
#aboutMe {
    background-color: #1d2028;
}

h2 {
    color: #ffffff;
}

span,
p {
    color: #7a89ab;
}

#whyWorkWithMe {
    background-color: #171920;
}

#recentWork {
    background-color: #87c856;
}

#recentWork span {
    color: #ffffff;
}

#recentWork img {
    width: 50%;
}

#viewWork{
    background-color: #fa225b;
}
</style>