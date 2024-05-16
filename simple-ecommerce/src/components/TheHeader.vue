<template>
    <header>
        <div class="bg-img"></div>
        <div class="overlay">
            <h1 class="text-title">YOUR FOOD <span>TO GO</span></h1>
            <button class="btn"><a href="#Orders">Order Now</a></button>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>
header{
    position: relative;
}

.bg-img{
    background: url(https://images.unsplash.com/photo-1555939594-58d7cb561ad1?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D) center/cover no-repeat;
    height: 100vh;
    width: 100%;
}

.overlay{
    position: absolute;
    top: 0;
    left: 0;
    height: 100vh;
    width: 100%;
    background: rgba(0,0,0,0.75 );
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}
.overlay h1 span{
    color:var(--prim-t_c); 
}

.overlay .btn{
    margin-top: 3rem;
    font-size: var(--font-size_md);
}

.overlay .btn a{
    color: var(--sec-t_c);
}
</style>