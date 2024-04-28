<template>
    <nav id="nav">
        <img src="../img/25068-6-bubbles-file.png" alt="logo" id="logo">
        <label for="logo" class="hover">Bubbling</label>
        <button class="btn hover">sign-up</button>
    </nav>
</template>

<style scoped>
:root {
    --prim-c: rgba(255,255,255,0.8);
    --sec-c: rgba(255,255,255,0.3);
}
#nav{
    position: relative;
    width: 80%;
    height: 80px;
    margin: 0 auto;
    padding-top: 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

#nav #logo {
    height: 70px;
    width: 60px;
}

label{
    position: absolute;
    left: 25px;
    top: 25px;
    font-size: 1.8rem;
    cursor: pointer;
    text-shadow: 1px 1px 2px #333;
}

label:hover {
    color: #fff;
}

.btn {
    border: 4px solid var(--sec-c);
    color: blue;
    outline: none;
    transition: 0.3 ease;
    border-radius: 25px;
    

}

.btn:hover{
    border: 2px solid var(--prim-c);
}

.btn:active{
    transform: scale(0.95);
    transition: 0.3s ease;
}

</style>