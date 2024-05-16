<template>
    <section id="Menu">
        <section id="Menus" class="menu-section">
            <h2 class="text_sub-title">Menu <span>of the week</span></h2>

            <div class="menu-container">
                <div class="Breakfast-container">
                    <aside>breakfast</aside>
                    <ul class="breakfast">
                        <li>Weekdays</li>
                        <li>7:00 - 10:00 AM</li>
                        <li>Breakfast of the Champions <span>$99.99</span></li>
                        <li>2 Eggs | 2 Bacon | 1 cup of Coffee</li>
                        <li>All you need for the day<span>$8.99</span></li>
                        <li>2 loaves of bread | 2 Butter | 1 cup of tea</li>
                    </ul>
                </div>
                <div class="Lunch-container">
                    <aside>Lunch</aside>
                    <ul class="Lunch">
                        <li>Weekdays</li>
                        <li>12:00 - 2:00 PM</li>
                        <li>Lunch of the Champions <span>$99.99</span></li>
                        <li>2 Eggs | 2 Bacon | 1 cup of Coffee</li>
                        <li>All you need for the day<span>$8.99</span></li>
                        <li>2 loaves of bread | 2 Butter | 1 cup of tea</li>
                    </ul>
                </div>
                <div class="Dinner-container">
                    <aside>Dinner</aside>
                    <ul class="Dinner">
                        <li>Weekdays</li>
                        <li>7:00 - 10:00 AM</li>
                        <li>Dinner of the Champions <span>$99.99</span></li>
                        <li>2 Eggs | 2 Bacon | 1 cup of Coffee</li>
                        <li>All you need for the day<span>$8.99</span></li>
                        <li>2 loaves of bread | 2 Butter | 1 cup of tea</li>
                    </ul>
                </div>
            </div>
        </section>
    </section>
</template>

<script setup>

</script>

<style scoped>
h2{
    font-family: var(--font-family_title);
}

.menu-section{
    padding: 2rem 0;
}

.menu-section h2{
    width: 300px;
    margin: auto;
    margin-bottom: 2rem;
}
.menu-section h2 span{
    color: var(--sec-t_c);
}

.menu-container{
    position: relative;
    margin-top: 2rem;
    max-width: 350px;
    border: 1px solid var(--prim-t_c);
    margin: auto;
    display: flex;
    flex-direction: column;
}

.Breakfast-container,
.Lunch-container,
.Dinner-container{
    position: relative;
    display: grid;
    grid-template-columns: 60px 290px;
    font-size: var(--font-size_sm);
    color: var(--sec-t_c);
    border-bottom: 5px solid black;
    letter-spacing: 1px;
}
.menu-container aside{
    transform: rotate(-90deg);
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: medium;
    font-family: var(--font-family_title);
}

.menu-container li:nth-child(odd){
    color: var(--prim-t_c);
    margin-top: .5rem;
}

.menu-container li span{
    color: yellow;
}
</style>