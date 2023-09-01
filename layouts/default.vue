<template>
    <div class="container">
        <header>
            <NuxtLink to="/" class="h1">Oluwatosin</NuxtLink>
                <nav>
                    <ul>
                        <li>
                            <NuxtLink to="/">Home</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/About">About</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/Service">Service</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/Self-care">Self-care Course</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/Speaking">Speaking</NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/Contact">Contact</NuxtLink>
                        </li>
                    </ul>
                </nav>
        </header>

        <!-- output the page content -->
        <div>
            <slot />
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
header {
    width: 80%;
    height: 10vh;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.h1 {
    font-size: 40px;
    font-weight: 600;
    color: coral;
}

nav {
    /* display: flex;
    justify-content: space-between;
    align-items: end; */
    display: flex-end;
}

ul {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
}

li {
    margin: 0 10px;
    list-style: none;
    font-size: 18px;
    font-weight: 600;
    color: black;
}

li:active {
    color: none;
}

a {
    text-decoration: none;
}

li .router-link-active {
    color: coral;
}</style>