<template>
    <nav id="Nav">
            <a href="../assets/vue.svg" id="Nav-logo"></a>
            <ul>
                <li>
                    <a href="#About">About</a>
                </li>
                <li>
                    <a href="#Service">Services</a>
                </li>
                <li>
                    <a href="#Contact">contact</a>
                </li>
            </ul>
        
        </nav>
</template>

<script>


</script>

<style scoped>
#Nav{
    height: 10vh;
    font-size: 2rem;
    display: flex;
    padding: 1rem;
    background-color: rgba(0, 0, 0, 0.1);
}

#Nav-logo{
    height: 60px;
    width: 60px;
    background-color: #fff;
    border-radius: 50%;
    display: flex;
    align-self: center;
}

#Nav ul{
    width: 100%;
    display: flex;
    justify-content: flex-end;
}

#Nav ul li{
    padding-left: 1rem;
}

#Nav ul li a{
    color: #fff;
    font-weight: bold;
    letter-spacing: 1px;
}
</style>