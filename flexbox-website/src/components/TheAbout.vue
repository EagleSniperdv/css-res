<template>
    <section id="About">
        <h2>About Us</h2>
        <div class="about-container">
            <div class="about-img"></div>
            <div class="about-description">
                <h3>About our Company</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Temporibus reprehenderit dolores adipisci iusto distinctio cumque animi! Sint officiis, aut quibusdam quia beatae commodi quasi necessitatibus saepe? Possimus deleniti itaque dolorum?</p>
                <button class="btn btn-danger">Learn More</button>
            </div>
        </div>
    </section>
</template>

<script>

</script>

<style scoped>
#About{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

#About .about-container{
    width: 1200px;
    display: flex;
    margin-top: 6rem;
}

#About .about-img{
    min-width: 550px;
    background-image: url("../public/vite.svg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    border-radius: 50%;
}

#About .about-description{
    padding-left: 2rem;
}
</style>