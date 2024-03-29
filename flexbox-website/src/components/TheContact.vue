<template>
    <section id="Contact">
        <h2>Contact Us</h2>
        <div class="contact-container">
            <div class="contact">
                <i class="fas fa-phone fa-3x"></i>
                <h3>Call Us</h3>
                <p>011111111</p>
                <p>022222222</p>
            </div>
            <div class="contact">
                <i class="fas fa-street-view fa-3x"></i>
                <h3>Visit Us</h3>
                <p>2453 Nairobi</p>
                <p>Some Street</p>
            </div>
            <div class="contact">
                <i class="fas fa-mail-bulk fa-3x"></i>
                <h3>Email Us</h3>
                <p>ifoa@gamaol.com</p>
                <p>wwww.wwwww.com</p>
            </div>
        </div>
    </section>
</template>

<script>

</script>

<style scoped>
#Contact {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

#Contact .contact-container{
    display: flex;
    flex-wrap: wrap;
    margin-top: 4rem;
    justify-content: space-evenly;
    align-items: center;
}

#Contact .contact{
    max-width: 300px;
    padding: 2rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #fff;
}

#Contact i{
    margin-bottom: 1rem;
}
#Contact i:hover{
    color: blue;
}


</style>