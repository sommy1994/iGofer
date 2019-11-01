<template>
    <div>
        <nav-bar />
          <section landing-content>
            <div class="landing-picture">
                <h2>A convenient and affordable way to get things done</h2>
                <p class="word pb-5">Choose from a pool of iGofer trained and verified professionals to <br> get your
                    job done.
                </p>
            </div>
        </section>
        <the-footer />
    </div>
</template>

<script>
import NavBar from '../components/HomePage/NavBar.vue';
import TheFooter from '../components/HomePage/TheFooter.vue';
export default {
    components: {
        'nav-bar': NavBar,
        'the-footer': TheFooter
    }
}
</script>

<style>

[landing-content]{
    margin-top: 50px;
}
    .landing-picture {
    width: 100%;
    height: 700px;
    /* background: linear-gradient(0deg, rgba(55, 7, 0, 0.02), rgba(55, 7, 0, 0.02)), url('/assets/img/homepage/picture.svg'); */
    background: linear-gradient(89.54deg, rgba(0, 0, 0, 0.53) -3.78%, rgba(0, 0, 0, 0.37) 50.18%, rgba(0, 0, 0, 0.1) 99.78%), url('/assets/img/homepage/picture.svg');
}
</style>