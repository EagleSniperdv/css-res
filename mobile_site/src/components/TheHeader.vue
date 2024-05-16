<template>
    <header>
        <div class="header-text">
            <div class="header-text_content">
                <h1>DonTech</h1>
                <h2>Solutions</h2>
                <button class="btn">
                    <i class="fas fa-book-open"></i>
                    <a href="#footer">Contact</a>
                </button>
            </div>
        </div>

        <div id="header-img">
            <!-- <img src="https://images.unsplash.com/photo-1714718085992-07ff9ec410eb?q=80&w=1938&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt=""> -->

        </div>
    </header>
</template>

<script setup>

</script>

<style scoped> 
#header-img {
    background: url(https://images.unsplash.com/photo-1714718085992-07ff9ec410eb?q=80&w=1938&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 50vh;
    flex: 0 1 60vw;
    margin: 0;
    animation: anime 2s ease-in-out;
}

header{
    text-shadow: 1px 1px 1px rgba(0, 0 ,0 , 0.5);
}

h1 {
    position: relative;
    color: red;
    font-size: 2.5rem;
}

h2{
    font-size: 1.3rem;
    text-transform: uppercase;
    color: #666;
}

.header-text {
    display: flex;
    flex: 0 1 40vw;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 0 1rem;
    height: 50vh;
    animation: anime 2s ease-in-out;
}

.btn{
    padding: 1rem 2rem;
    border: 1px #ddd solid;
    outline: none;
    margin: 2rem;
    border-radius: 50px;
    box-shadow: 0 0 5px 1px rgba(0, 0 ,0 , 0.3);
    background-color: #333;
}

.btn a,
.btn i{
    color: #fff;
    font-size: 1.2rem;
    padding-right: 1rem;
}

@keyframes anime {
    0%{
        opacity: 0;
    }
    100%{
        opacity: 1;
    }
}

</style>