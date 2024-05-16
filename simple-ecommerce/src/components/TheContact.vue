<template>
    <section id="Contact">
        <h2 class="text_sub-title">Contact <span> Us</span></h2>
        <div class="contact-container">
            <div class="phone">
                <i class="fas fa-phone icon"></i>000000000
            </div>
            <div class="address">
                <i class="fas fa-map icon"></i>Street
                54,city,country.
            </div>
            <div class="mail">
                <i class="fas fa-envelope icon"></i>hcbdsbhd@gmail.com
            </div>
            <div class="social">
                <h4>Follow us</h4>
                <i class="fab fa-facebook icon"></i>
                <i class="fab fa-instagram icon"></i>
                <i class="fab fa-twitter icon"></i>
                <i class="fab fa-pinterest icon"></i>
            </div>
        </div>
        <form action="#" class="contact-form">
            <div class="input-container">
                <label for="">First Name</label>
                <input type="text" placeholder="Your Name..." required>
            </div>

            <div class="input-container">
                <label for="">Last Name</label>
                <input type="text" placeholder="Your Name..." required>
            </div>

            <div class="input-container">
                <label for="">Customer from..</label>
                <select name="Customer" id="Customer">
                    <option value="restaurant">Restaurant</option>
                    <option value="ToGo">ToGo</option>
                </select>
            </div>

            <div class="input-container">
                <label for="">Subject</label>
                <textarea 
                    name="" 
                    id=""
                    placeholder="Write Something..."
                    cols="30"
                    rows="700"
                    required
                    ></textarea>
            </div>

            <button 
                type="submit"
                value="submit"
                class="btn"
            >Submit</button>
        </form>
    </section>
</template>

<style scoped>

h2{
    font-family: var(--font-family_title);
}

#Contact h2 span {
    color: var(--sec-t_c);
}

.contact-container{
    padding: 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.contact-container i {
    margin-right: 1rem;
}

.contact-container .social{
    display: flex;
    align-items: center;
}

.contact-container .social h4{
    margin-right: 1rem;
}

.contact-container div{
    margin-bottom: 1rem;
}

.contact-form{
    width: 340px;
    margin: auto;
}

.input-container{
    display: flex;
    flex-direction: column;
    margin-bottom: 1rem;
    margin-top: 1rem;

}

.input-container label{
    margin-bottom: .5rem;
    color: var(--prim-t_c);
}

.contact-form input,
.contact-form select,
.contact-form textarea {
    height: 40px;
    border: none;
    outline: none;
    border-radius: 5px;
    padding-left: .5rem;
}

.contact-form button[type = "submit"] {
    width: 100%;
    border-radius: 5px;
    margin-bottom: 2rem;
}

</style>

<script>

</script>