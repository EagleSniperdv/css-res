<template>
    <nav id="Nav" class="navigation">
        <div class="logo">To-Go</div>
        <ul class="nav-list" v-if="showNav">
        <li><a href="#Home" class="nav-link">Home</a></li>
        <li><a href="#Menu" class="nav-link">Menu</a></li>
        <li><a href="#Orders" class="nav-link">Orders</a></li>
        <li><a href="#Contact" class="nav-link">Contact</a></li>
        <div class="nav-socials">
            <i class="fab fa-facebook icon"></i>
            <i class="fab fa-instagram icon"></i>
            <i class="fab fa-twitter icon"></i>
            <i class="fab fa-pinterest icon"></i>
        </div>
        </ul>
        <button id="Nav-btn" class="btn btn-nav" @click="toggleNav">
        <i class="fas fa-bars"></i>
        </button>
    </nav>
</template>

    <script>
    export default {
    data() {
        return {
        showNav: false
        };
    },
    methods: {
        toggleNav() {
        this.showNav = !this.showNav;
        }
    }
    };
    </script>
<style scoped>
    .nav-phone_inactive {
        display: none;
    }
.navigation{
    display: flex;
    position: fixed;
    z-index: 3;
    background-color: rgba(0, 0, 0, 0.9);
    width: 100%;
    height: 50px;
    padding-top: .5rem;
    justify-content: space-between;
}

.logo{
    font-family: var(--font-family_title);
    font-size: var(--font-size_xl);
    background-color: var(--logo-c);
    /* color: var(--sec-t_c); */
    padding: 0 1rem;
    margin-left: 0.5rem;
}

.btn-nav{
    height: 40px;
    width: 40px;
    margin-right: 0.8rem;
}

.nav-list{
    position: absolute;
    background-color: rgba(0, 0, 0, 0.8);
    border: black;
    height: 100vh;
    width: 80vw;
    display: flex;
    flex-direction: column;
    padding-left: 1rem;
    padding-top: 2rem;
}

.nav-list li{
    width: 100%;
    border-bottom: 1px solid var(--prim-t_c);
    padding: 0.5rem 0;
    margin: 1rem 0;
}

.nav-link{
    color: var(--sec-t_c);
    text-shadow: 1px 2px 1px var(--prim-t_c);
    font-size: var(--font-size_md);
    margin: 1rem;
    text-transform: uppercase;
    font-weight: 900;
    letter-spacing: 2px;
}

.nav-socials{
    font-size: var(--font-size_xl);
    display: flex;
    margin-top: 25vh;
    justify-content: space-evenly;
    color: var(--prim-t_c);
}

@media (min-width:700px) {
    .navigation {
        padding-top: 1rem;
    }

    .nav-socials {
        margin-top: 55vh;
    }

    .nav-link {
        font-size: var(--font-size_xl);
    }
}


</style>