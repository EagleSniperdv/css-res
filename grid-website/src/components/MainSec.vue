<template>
<main>
    <section id="News">
        <div class="card-container">
            <h3 class="card-title">
                <strong>Naboth Ongwenyi </strong>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, culpa?

             </h3>
             <h5 class="card-subtitle">
                <a href="">View work</a>  /
                <a href="">View Profile</a>  /
                <a href="">Post date</a>  /
             </h5>
             <img src="../assets/one.png" alt="image" class="card-img"/>
        </div>
        <div class="card-container">
            <h3 class="card-title">
                <strong>Naboth Ongwenyi </strong>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, culpa?

             </h3>
             <h5 class="card-subtitle">
                <a href="">View work</a>  /
                <a href="">View Profile</a>  /
                <a href="">Post date</a>  /
             </h5>
             <img src="../assets/one.png" alt="image" class="card-img"/>
        </div>
        <div class="card-container">
            <h3 class="card-title">
                <strong>Naboth Ongwenyi </strong>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, culpa?

             </h3>
             <h5 class="card-subtitle">
                <a href="">View work</a>  /
                <a href="">View Profile</a>  /
                <a href="">Post date</a>  /
             </h5>
             <img src="../assets/one.png" alt="image" class="card-img"/>
        </div>
        <div class="card-container">
            <h3 class="card-title">
                <strong>Naboth Ongwenyi </strong>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga, culpa?

             </h3>
             <h5 class="card-subtitle">
                <a href="">View work</a>  /
                <a href="">View Profile</a>  /
                <a href="">Post date</a>  /
             </h5>
             <img src="../assets/one.png" alt="image" class="card-img"/>
        </div>
    </section>
</main>

</template>

<style scoped>
.card-container{
    min-width: 300px;
    height: 100%;
    /* display: grid;
    grid-template-columns: 1fr; */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    position: relative;
}

.card-title {
    font-family: "PT Sans Narrow", sans-serif;
    font-weight: 100;
    padding: 0.4rem 0;

}


.card-title strong {
    font-weight: 600;
    font-size: 1.7rem;
}
.card-title strong:hover {
    cursor: pointer;
    text-decoration: underline;
}

.card-container:hover::before {
    cursor: pointer;
    position: absolute;
    content: "Read more...";
    text-align: center;
    text-decoration: underline;
    z-index: 3;
    top: 60%;
    left: 5%;
    height: 30px;
    width: 150px;
    color: #fff;
    background-color: rgba(51, 50, 50, 0.5);
    text-shadow: 1px 1px 1px rgba(20, 20, 20, 0.4);
    border: 1px solid black;
    font-size: 1.3rem;
    border-radius: 5px;
    display: grid;
    grid-template-columns: 1fr;

    place-self: center;

}

.card-subtitle {
    padding: 0.3rem 0;
    text-transform: uppercase;
}
.card-subtitle a{
 color: #777;
 font-weight: 400;
 letter-spacing: 1px;
}
.card-subtitle a:hover{
    cursor: pointer;
    text-decoration: none;
    color: #111;
}

.card-img {
    width: 100%;
}
.card-img:hover {
    cursor: pointer;
    filter: blur(2px);

}

section {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.3rem;
}

section:nth-child(1) {
    grid-column: 1/3;
    grid-row: 1/2;
    align-self: stretch;

}
section:nth-child(2) {
    grid-column: 3/3;
    grid-row: 1/3;
    align-self: stretch;

}
section:nth-child(3) {
    grid-column: 1/3;
    grid-row: 2/2;
    align-self: stretch;

}
section:nth-child(4) {
    grid-column: 1/3;
    grid-row: 3/3;
    align-self: stretch;

}


</style>