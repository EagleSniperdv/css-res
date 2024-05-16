<template>
    <section id="Orders" class="orders-section">
        <h2 class="text_sub-title">Order<span> Now</span></h2>
        <div class="cards-container">

            <div id="Slide" class="card-body">
                <h4 class="card-title">King Burger</h4>
                <p class="card-description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quisquam deleniti doloribus voluptatem labore animi pariatur libero ad perferendis quidem.</p>
                <div class="break"></div>
                <div class="card-price">$15.99</div>
                <div class="input-container">
                    <input type="number" name="" id="Amount" placeholder="0">
                    <label for="Amount"> Amount</label>
                </div>
                <button class="btn btn-order">Add to Order</button>
            </div>

            <div id="Slide" class="card-body">
                <h4 class="card-title">King Burger</h4>
                <p class="card-description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quisquam deleniti doloribus voluptatem labore animi pariatur libero ad perferendis quidem.</p>
                <div class="break"></div>
                <div class="card-price">$15.99</div>
                <div class="input-container">
                    <input type="number" name="" id="Amount" placeholder="0">
                    <label for="Amount"> Amount</label>
                </div>
                <button class="btn btn-order">Add to Order</button>
            </div>

            <div id="Slide" class="card-body">
                <h4 class="card-title">King Burger</h4>
                <p class="card-description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quisquam deleniti doloribus voluptatem labore animi pariatur libero ad perferendis quidem.</p>
                <div class="break"></div>
                <div class="card-price">$15.99</div>
                <div class="input-container">
                    <input type="number" name="" id="Amount" placeholder="0">
                    <label for="Amount"> Amount</label>
                </div>
                <button class="btn btn-order">Add to Order</button>
            </div>

        </div>
    </section>
</template>

<style scoped>
h2{
    font-family: var(--font-family_title);
}

.orders-section h2 span{
    color: var(--sec-t_c);
}

.cards-container{
    position: relative;
}

.card-body{
    width: 280px;
    background-color: var(--prim-bg_c);
    border-radius: 10px;
    margin: .5rem auto;
    padding: 1rem;
    animation: fade .5s ease-out;
}

.card-title{
    color: var(--prim-t_c);
    font-size: var(--font-size_md);
    margin-bottom: 1rem;
}

.card-description{
    margin-bottom: 1rem;
}

.break{
    width: 90%;
    height: 1px;
    margin-bottom: 1rem;
    /* background-color: var(--prim-t_c); */
    animation: liney 2s linear infinite;
}

.card-price{
    color: var(--prim-t_c);
    margin-bottom: 2rem;
    font-size: var(--font-size_md);
}

.card-body .input-container{
    display: block;
}
.card-body .input-container input[type="number"]{
    width: 50px;
    margin: 0 1rem 1rem 0;
    background-color: var(--dark-bg_color);
    color: var(--sec-t_c);
    outline: none;
    border-radius: 5px;
    text-align: center;
    padding: 0.5rem;
}

@keyframes liney {
    from{
        background-color: var(--prim-t_c);
        opacity: 0.2;
    }
    to{
        background-color: var(--prim-t_c);
        opacity: 1;
    }
}

@keyframes fade {
    from{
        opacity: 0.4;
    }
    to {
        opacity: 1;
    }
}
</style>