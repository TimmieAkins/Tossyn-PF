<template>
    <main>
        <div class="container">
            <div class="empty">
            </div>
            <div class="about-writeup">
                <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt deleniti, porro sequi sit incidunt dolorum.</h1>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ducimus vel officia itaque libero, quasi excepturi accusantium mollitia, nemo totam labore quas in esse aperiam! Accusantium illum nemo sed, vel ipsam beatae. Assumenda eos nihil debitis laboriosam inventore sequi labore qui, dolore neque aperiam modi pariatur corporis quisquam magnam excepturi illum!</p> 
            </div>
        </div>
    </main>
</template>

<style scoped>
main {
width: 100%;
height: 90vh;
padding: 40px;
background-image: url(..\img\pexels-karolina-grabowska-7602594.jpg);
background-repeat: no-repeat;
background-size: cover;
}

.container {
width: 100%;
height: 80vh;
margin: 0 auto;
display: flex;
flex-direction: row;
align-items: center;
justify-content: flex-start;
}


/* .container div {
width: 50%;
height: 100%;
} */

.empty {
    flex: 1;
    width: 50%;
}


.about-writeup {
flex: 2;
width: 50%;
padding: 10px;
text-align: right;
}

.about-writeup h1 {
font-size: 50px;
}
</style>