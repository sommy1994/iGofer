<template>
    <div>
        <nav-bar />
        <footer />
    </div>
</template>

<script>
import NavBar from '../components/HomePage/NavBar.vue';
import NavBar from '../components/HomePage/Footer.vue';
export default {
    components: {
        'nav-bar': NavBar,
        'footer': Footer
    }
}
</script>