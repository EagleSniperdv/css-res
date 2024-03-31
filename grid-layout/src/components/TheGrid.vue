<template>
<h1>CSS GRID</h1>
<section id="Parent">
    <h2>properties of the parent</h2>
    <h3>Display Grid</h3>
    <div class="Grid-container">
        <div class="Grid_item">item-1</div>
        <div class="Grid_item">item-2</div>
        <div class="Grid_item">item-3</div>
        <div class="Grid_item">item-4</div>
        <div class="Grid_item">item-5</div>
        <div class="Grid_item">item-6</div>
    </div>
</section>
</template>

<style scoped>
.Grid-container {
  /* display: grid; */
  background-color: #333333;
  color: #fff;
  box-shadow: 0 0 10px 2px;
  height: 300px;
  /* grid-template-columns: 100px 100px auto 250px 150px;

  grid-template-columns: 25% 100px auto;
  grid-template-rows: 200px auto;

  grid-template-columns: 175px 175px 175px;

  grid-template-columns: repeat(3, 200px);
  grid-template-columns: repeat(3, 33.3333%); */
  /* grid-template-columns: repeat(4, 5em); */

  /* grid-template-columns: repeat(4, 1fr);
  grid-template-columns: 1fr;
  grid-template-columns: 1fr 1fr;
  grid-template-columns: 1fr 2fr;
  grid-template-columns: 1fr 20% 1fr;

  grid-template-columns: repeat(4, 2fr);
  grid-template-rows: repeat(3, 1fr); */
}
.Grid_item {
    color: #fff;
    border-radius: 10px;
    text-align: center;
    font-size: 1.3rem;

    border: 1px solid;
}

.Grid_item:nth-child(odd) {
  background-color: orange;
}
.Grid_item:nth-child(even) {
  background-color: red;
}

/* Grid-Template Area
.Grid_item:nth-child(1) {
    grid-area: nav;
}

.Grid_item:nth-child(2) {
    grid-area: header;
}
.Grid_item:nth-child(3) {
    grid-area: main;
}
.Grid_item:nth-child(4) {
    grid-area: section;
}
.Grid_item:nth-child(5) {
    grid-area: said;
}
.Grid_item:nth-child(6) {
    grid-area: footer;
} */
/* .Grid-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: auto;
    grid-template-areas: 
        "nav nav nav nav"
        "said header header header"
        "said main main ."
        "said section section ." 
        "footer footer footer footer"
} */

/* Grid Template */
/* .Grid-container{
    display: grid;
    grid-template: 
        "nav nav nav nav" 80px
        "said header header header" auto
        "said main main ." auto
        "said section section ."  auto
        "footer footer footer footer" 30px
        / auto 50px auto
    ;
} */

/* .Grid-container {
    grid-column-gap: 10px;
    grid-row-gap: 10px;
    gap: 20px 10px;
} */

.Grid-container {
    display: grid;
    grid-template-columns: repeat(2,1fr);
    justify-items: start;
    justify-items: stretch;
}
</style>