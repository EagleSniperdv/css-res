<template>
  <header>
    <h1>This is an Animation</h1>
    <p>Animate your css</p>
  </header>
    <section class="animation-section">
      <h2 style="font-size: 3rem;">Animation with colors</h2>
      <div class="animation-color"></div>
    </section>
    <section class="animation-section">
      <h2 style="font-size: 3rem;">Animation direction</h2>
      <div class="animation-direction"></div>
    </section>
    <section class="animation-section">
      <h2 style="font-size: 3rem;">Animation speed curve</h2>
      <div class="animation-speed"></div>
    </section>
    <section class="animation-section">
      <h2 style="font-size: 3rem;">Aniation fill mode</h2>
      <div class="animation-fill"></div>
    </section>
    <section class="animation-section">
      <h2 style="font-size: 3rem;">Animation short hand properties</h2>
      <div class="animation-shorthand"></div>
    </section>
</template>

<style scoped>

  header {
    width: 600px;
    position: relative;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
    text-align: center;
    height: 95vh;
  }

  .animation-section {
    display: block;
    height: 100vh;
    width: 700px;
    text-align: center;
    margin: auto;
  }

  @keyframes animation-name{
    0% {
      opacity:0;
      transform:translateX(-100px);
    }
    50% {

    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }

    from {

    }

    to {

    }
  }
  @keyframes animation-name2{
    0% {
      opacity:0;
      transform:translateX(-100px);
    }
    50% {
      transform: translateY(80px);
    }
    100% {
      opacity: 1;
      transform: translateX(0);
    }

    from {

    }

    to {

    }
  }

  @keyframes colors {
    from {
      background-color: red;
    }
    to {
      background-color: yellow;
    }
  }

  @keyframes animation-direction {
    0% {
      background-color: #ff0000;
      left: 0px;
      top: 0px;
    }
    25% {
      background-color: #ffff00;
      left: 200px;
      top: 0px;
    }
    50% {
      background-color: #0000ff;
      left: 200px;
      top: 200px;
    }
    75% {
      background-color: #008000;
      left: 0px;
      top: 200px;
    }
    100% {
      background-color: #ff0000;
      left: 0px;
      top: 0px;
    }
  }

  @keyframes motion_timing {
    from {
      left: 0;
    }

    to {
      left: 600px;
      background-color: blue;
    }
  }

  @keyframes anime-forward{
    from {
      top: 0;
    }

    to {
      top: 200px;
      background-color: green;
    }
  }
  @keyframes anime-backward{
    from {
      top: 0;
    }

    to {
      top: 200px;
      background-color: yellow;
    }
  }
  @keyframes anime-both{
    from {
      top: 0;
    }

    to {
      top: 200px;
      background-color: purple;
    }
  }
  @keyframes anime-shorthand {
    0% {
      left: 0;
      top: 0;
    }
    25% {
      background-color: yellow;
      left: 200px;
      top: 0;
    }
    50% {
      background-color: blue;
      left:200px;
      top: 200px;
    }
    75%{
      background-color: green;
      left: 0px;
      top: 200px;
    }
    100%{
      background-color: red;
      left: 0;
      top: 0;
    }
  }

  h1{
    animation: animation-name;
    animation-duration: 5s;
    margin-top: 2rem;
    font-size: 5rem;
    animation-delay: 3s;
  }

  p {
    font-size: 2rem;
    text-transform: uppercase;
    animation: animation-name2 5s backwards alternate;
    animation-delay: 2s;
  }

  .animation-color {
    width: 100px;
    height: 100px;
    margin: auto;
    background-color: red;
    animation: colors;
    animation-duration: 4s;
    animation-iteration-count: 3;
  }

  .animation-direction {
    width: 100px;
    height: 100px;
    background-color: red;
    position: relative;
    animation: animation-direction;
    animation-duration: 4s;
    animation-direction: normal;
  }

  .animation-speed {
    width: 100px;
    height: 50px;
    background-color: red;
    position: relative;
    animation: motion_timing;
    animation-duration: 5s;
    animation-iteration-count: 3;
    animation-timing-function: ease ;
  }

  .animation-fill {
    width: 200px;
    height: 200px;
    background-color: red;
    position: relative;
    animation: anime-forward;
    /* animation: anime-both;
    animation: anime-backward; */
    animation-duration: 3s;
    animation-fill-mode: forwards;
  }

  .animation-shorthand {
    width: 200px;
    height: 200px;
    background-color: purple;
    position: relative;
    margin-top: 3rem;
    /* animation: anime-shorthand;
    animation-duration: 5s;
    animation-timing-function: linear;
    animation-delay: 2s;
    animation-iteration-count: infinite;
    animation-direction: alternate; */

    animation: anime-shorthand 5s linear 2s infinite alternate;
  }
</style>