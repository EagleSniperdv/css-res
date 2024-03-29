<template>
    <Section id="Service">
        <h2>Services</h2>
        <div class="service-container">
            <div class="service">
                <h3>Web Design</h3>
                <i class="fas fa-pen-nib fa-3x"></i>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptate, vitae?</p></div>
            <div class="service">
                <h3>Web Development</h3>
                <i class="fas fa-pencil-ruler fa-3x"></i>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, ipsam.</p></div>
            <div class="service">
                <h3>Web Hosting</h3>
                <i class="fas fa-database fa-3x"></i>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus, esse!</p></div>
        </div>
    </Section>
</template>

<script>

</script>

<style scoped>
#Service h2{
    color: #fff;
}

#Service .service{
    background-color: #fff;
    max-width: 300px;
    box-shadow: 0 0 15px 5px;
    margin: 1rem;
    padding: 2rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

#Service .service:hover{
    cursor: pointer;
    transform: scale(1.01);
    transition: 0.5s ease;
    background-color: #555;
    color: #fff;
}

#Service{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 2rem;
}

#Service .service-container{
    display: flex;
    flex-wrap: wrap;
    margin-top: 4rem;
    justify-content: space-around;
}
</style>