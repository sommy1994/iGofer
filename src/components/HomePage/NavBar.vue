<template>
    <div>
        <header class="fixed-top">
            <nav class="navbar navbar-expand-lg navbar-light">
                <!-- logo -->
                <router-link to="/">
                 <img class="logo" src="/assets/img/logo.svg" alt="logo">
                    </router-link>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <!-- menu -->
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav mr-auto">
                        <router-link id="sign-in" class="nav-link" to="/services" tag="li" active-class="active" exact>Services</router-link>
                        <router-link id="sti
                        " class="nav-link" to="/store" tag="li" active-class="active">Store</router-link>

                    </ul>
                    <ul class="navbar-nav ml-auto pr-5">
                        <router-link id="join" class="nav-link" to="/join" tag="li" active-class="active">Join as a pro</router-link>
                        <router-link id="sign-up" class="nav-link" to="/signup" tag="li" active-class="active">Sign up</router-link>
                        <router-link id="login" class="nav-link" to="/login" tag="li" active-class="active">Log In</router-link>
                    </ul>
                </div>
            </nav>
        </header>

    </div>
</template>

<script>

export default {

}
</script>

<style scoped>
    nav {
        left: 0em;
        top: 0em;
        background-color: #FFFFFF;
        height: 3.75em;
        box-shadow: 0e, 0.25em 0.625em rgba(0, 0, 0, 0.25);
    }


    .logo {
        margin-left: 7.5em;
        top: 0.75em;
        width: 105px
    }


    li {
        font-family: "Avenir Next LT Pro";
        font-size: 0.875em;
        font-weight: 500;
        line-height: 1.0625em;
        text-align: center;
        color: #333456;
        cursor: pointer;
    }

    #nav {
        padding: 30px;
    }

    #nav a {
        font-weight: bold;
        color: #2c3e50;
    }

    #nav a.router-link-exact-active {
        color: #42b983;
    }

    </style>