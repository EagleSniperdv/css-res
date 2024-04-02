<template>
  <h1 id="title">transitions and rotations</h1>
  <h2>Transition properties</h2>
  <div></div>

  <hr>

  <h2>transition timing function prop</h2>

  <div id="div1">linear</div>
  <div id="div2">ease</div>
  <div id="div3">ease-in</div>
  <div id="div4">ease-out</div>
  <div id="div5">ease-in-ot</div>

  <hr>

  <h2>transition delay props</h2>

  <div class="delay"></div>

  <hr>

  <h2>transformation and rotation</h2>
  <div class="transformation"></div>

  <hr>
  <h2>transition shorthand</h2>
  <div class="shorthand"></div>


</template>

<style scoped>
  #title {
    font-size: 6rem;
    margin: 2rem;
  }

  div {
    width: 100px;
    height: 100px;
    background-color: red;
    color: azure;
    transition: width 3s;
    transition: width 2s, height 5s;
  }

  div:hover {
    width: 400px;
    height: 300px;
  } 

  #div1 {
    background-color: blue;
    transition-timing-function: linear;
  }

  #div2 {
    background-color: green;
    transition-timing-function: ease;
  }

  #div3 {
    background-color: yellow;
    transition-timing-function: ease-in;
    color: black;
  }

  #div4 {
    background-color: purple;
    transition-timing-function: ease-out;
    color: black;
  }

  #div5 {
    background-color: purple;
    transition-timing-function: ease-in-out;
    color: black;
  }

  div.delay {
    width: 100px;
    height: 100px;
    transition: width 3s;
    transition-delay: 1s;
  }

  div.delay:hover {
    width: 500px;
  }

div.transformation {
  width: 100px;
  height: 100px;
  background-color: #333;
  transition: width 2s, height 2s, transform 2s;
}

div.transformation:hover {
  width: 300px;
  height: 300px;

  transform: rotate(180deg);
  transform: rotate(1turn);
  transform: scale(0.1);
  transform: translateX(120px);
}

div.shorthand {
  width: 150px;
  height: 150px;
  background-color: brown;

  /* transition: pro dur, timing-func, delay; */
  transition: width 4s, height 2s, background-color 2s, transform 2s, ease-in-out 2s;
}

div.shorthand:hover {
  width: 300px;
  height: 400px;
  background-color: red;
  transform: rotate(180deg);
}
</style>