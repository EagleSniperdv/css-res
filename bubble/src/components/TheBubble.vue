<template>
    <div id="bubbles">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
        <img src="../img/25068-6-bubbles-file.png" alt="bubble">
    </div>
</template>

<style scoped>
#bubbles {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
    position: absolute;
    bottom: 0;
}
#bubbles img{
    width: 85px;
    height: 100px;
    opacity: .3;
    align-self: center;
    animation: bubble 7s linear infinite;

}

@keyframes bubble {
    0%{
        transform: translateY(0);
        opacity: 0;
    }
    30%{
        opacity: 0.3;
    }
    50%{
        opacity: 0.5;
    }
    70%{
        opacity: 0.7;
    }
    100%{
        transform: translateY(-80vh);
        opacity: 1;
    }

}
#bubbles img:nth-child(1) {
    animation-delay: 2s ;
    width: 20px;
    height: 25px;
}
#bubbles img:nth-child(2) {
    animation-delay: 1s ;
    width: 40px;
    height: 45px;
}
#bubbles img:nth-child(3) {
    animation-delay: 3s ;
}
#bubbles img:nth-child(4) {
    animation-delay: 2s ;
    width: 30px;
    height: 35px;
}
#bubbles img:nth-child(5) {
    animation-delay: 8s ;
    width: 50px;
    height: 55px;
}
#bubbles img:nth-child(6) {
    animation-delay: 2s ;
    width: 30px;
    height: 35px;
}
#bubbles img:nth-child(7) {
    animation-delay: 5s ;
    width: 20px;
    height: 25px;
}
#bubbles img:nth-child(8) {
    animation-delay: 3s ;
    width: 50px;
    height: 55px;
}
</style>