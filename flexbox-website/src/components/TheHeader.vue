<template>
    <header id="Header">
        <h1>FlexBox Website</h1>
        <h3>Responsive web Design</h3>
        <button class="btn btn-success btn-lg"><a href="Contact">Contact us</a></button>
    </header>
</template>

<style scoped>
    button{
        background-color: green;
    
    }

    #Header{
        height: 90vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    #Header h1 {
        font-size: 10rem;
        text-align: center;
        margin-bottom: 4rem;
    }

    #Header h3{
        color: rgba(0, 0, 0, 0.7);
    }

    #Header .btn-success{
        margin-top: 2rem;
    }
    #Header .btn-success a{
        color: #fff;
        text-transform: uppercase;
    }


</style>