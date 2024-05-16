<template>
    <footer id="footer">
        <h3>Contact Us</h3>
        <div class="contact-container">
            <div>
                <i class="fas fa-envelope"></i>
                <a href="#footer">Email Us</a>
            </div>
            <div>
                <i class="fas fa-phone-volume"></i>
                <b>0115414418</b>
            </div>
            <div>
                <h4>Follow us</h4>
                <div class="social-media-icons">
                    <i class="fab fa-facebook"></i>
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-youtube"></i>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
#footer {
    text-align: center;
    padding: 2rem 1rem;
    margin: auto;
    background-color: #333;
    color: #ddd;
    text-shadow: 1px 4px 2px rgba(0, 0, 0 0.2);

}

#footer a {
    color: #ddd;
}
#footer a:hover {
    color: blue;
    text-decoration: underline;
}
#footer i{
    padding: 0.5rem 1rem;
    font-size: 2rem;
}

#footer h3{
    margin-bottom: 1rem;
    font-size: 2rem;
}
.contact-container>div{
    padding: 1.25rem 0;
    display: flex;
    flex-direction: column;
}
.social-media-icons{
    display: flex;
    flex-direction: row;
    justify-content: center;
}

@media (min-width:500px) {
  .contact-container{
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }
}
</style>

<script setup>


</script>