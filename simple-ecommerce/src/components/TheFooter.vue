<template>
    <footer>
        <p>2080 &copy; DonTech Solutions <b> | </b> To-Go-All rights Reserved</p>
        <p>
            <a href="#">Impressions</a> - <a href="#">Personal Data</a> - <a href="#">Cookies Settings</a>
        </p>
    </footer>
</template>

<style scoped>
footer {
    border-top: 1px solid var(--prim-t_c);
    color: var(--prim-t_c);
    padding: 1rem;
    display: grid;
    grid-template-columns: 1fr;
    text-align: center;
}

footer p b,footer p a{
    color: var(--sec-t_c);
}

footer p {
    margin-bottom: 1rem;
}

@media (min-width:700px) {
    footer {
        font-size: var(--font-size_md);
    }
}
</style>