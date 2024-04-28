<template>
    <header id="header">
        <h4>Hello and Welcome to</h4>
        <h1>CSS3 Animations <br> & <br> Transitions</h1>
        <button class="btn btn-plus hover">Animate</button>
    </header>
</template>

<style scoped>
#header{
    position: absolute;
    top: 50%;
    left: 30%;
    transform: translateY(-50%);
    color: #fff;
    display: flex;
    flex-direction: column;
}
h1{
    font-size: 4rem;
    margin: 3rem 0;
    letter-spacing: 1px;
    text-shadow: 1px 1px 2px #333;
    font-family: "Tilt Neon",sans-serif;;
}
@keyframes plus{
    0% {
        opacity: 0;
    }
    30% {
        opacity: 1;
    }
    70% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
    
}

.btn-plus{
    animation: plus 3s cubic-bezier(0.075, 0.82, 0.165, 1) infinite;
}

.btn-plus:hover{
    animation: none;
}
</style>