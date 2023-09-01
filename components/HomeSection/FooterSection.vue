<template>
    <div>
        <footer>
            <div class="thefooter">
                <div class="container">
                    <div class="con-foot">
                        <div class="footer-ex">
                            <h2>EXPLORE</h2>
                            <div class="footer-link">
                                <ul>
                                    <li>
                                        <NuxtLink to="/">Home</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="/about">About</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="/services">Services</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="/self-care">Self-care Course</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="/speaking">Speaking</NuxtLink>
                                    </li>
                                    <li>
                                        <NuxtLink to="/contact">Contact</NuxtLink>
                                    </li>
                                </ul>
                            </div>
                            <div class="footer-contact">
                                <button>CONTACT US</button>
                                <div class="footer-icons">
                                    <div class="facebook">
                                        <i class="fa-brands fa-square-facebook" style="color: #0645b1;"></i>
                                    </div>
                                    <div class="x">
                                        <i class="fa-brands fa-square-x-twitter" style="color: #0c0c0e;"></i>
                                    </div>
                                    <div class="insta">
                                        <i class="fa-brands fa-square-instagram" style="color: #f90b0b;"></i>
                                    </div>
                                    <div class="youtube">
                                        <i class="fa-brands fa-square-youtube" style="color: #ff1f1f;"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="footer-words">
                        <div class="word-h3">
                            <h3>Get your Monday Reminder</h3>
                            <p>Receive a dose of inspiration and love directly in your inbox every week.</p>
                        </div>
                        <div class="privacy">
                            <ul>
                                <li>
                                    <NuxtLink to="/privacy">Privacy Policy</NuxtLink>
                                </li>
                                <li>
                                    <NuxtLink to="/terms">Teams To Use</NuxtLink>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <h4> copyright &copy Oluwatosin Akinde</h4>
            </div>
        </footer>
    </div>
</template>

<style scoped>
footer {
    width: 100%;
    display: flex;
    flex-direction: column;
}

.thefooter {
    width: 100%;
    height: 300px;
    display: flex;
    flex-direction: row;
    gap: 20px;
    align-items: flex-start;
    justify-content: space-between;
    background-color: peru;
}

.container {
    width: 80%;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 10px;
}

.con-foot {
    display: flex;
    justify-content: flex-start;
    align-items: start;
}

.footer-ex {
    width: 250px;
    margin-right: 30px;
    background-color: rgb(200, 237, 250);
    position: relative;
    top: -45px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
}

button {
    width: 150px;
    height: 25px;
    margin: 10px 0;
    background-color: black;
    color: beige;
    border: none;
    border-radius: 10px;
}

.footer-icons {
    margin: 10 0 20 0;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.footer-icons div {
    width: 20px;
    height: 20px;
}

i {
    width: 100%;
    height: 100%;
}

h2 {
    font-size: 24px;
    margin: 20px 0
}

ul {
    /* margin: 0 20px; */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    list-style-type: none;
}

li {
    margin: 0.3rem 0;
    font-size: 1rem;
}

a {
    text-decoration: none;
    color: #222831;
    font-weight: bold;
    border-bottom: 2px solid transparent;
    padding-bottom: 0.25rem;
    transition: all .50s ease;
}

.footer-words {
    margin: 30px 20px;
    display: flex;
    flex-direction: column;
    align-items: end;
    justify-content: start;
}

.word-h3 {
    text-align: end;
}


.copyright {
    width: 100%;
    height: 25px;
    background-color: indianred;
    text-align: center;
}

.copyright h4 {
    padding: 5px 0;
}
</style>