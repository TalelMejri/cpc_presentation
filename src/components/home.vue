<template>
    <div class="page-container" id="home">
        <div class="container d-flex justify-content-center align-items-center gap-2">
            <div data-aos="zoom-in">
                <img src="../assets/images/logo.png" alt="logo club" class="animated-logo" >
            </div>
            <div class="text-container" data-aos="fade-left">
                <p>
                    <VueTypewriterEffect :strings="['CPC', 'Competitive Programming Club']"></VueTypewriterEffect>
                    <br>
                    Enicarthage
                </p>
            </div>
        </div>
        <div class="text-center para" data-aos="fade-left">
            Welcome to the Competitive Programming Club (CPC) at Enicarthage—where passion for problem-solving meets
            advanced skills! Here, every coder is empowered to grow, excel, and push their limits. Join us in mastering
            the art of competitive programming and unlocking boundless opportunities for the future.
        </div>
    </div>
</template>

<script>
import VueTypewriterEffect from "vue-typewriter-effect";
export default {
    components: {
        VueTypewriterEffect
    }
}
</script>

<style scoped>
.page-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    padding: 2rem;
    padding-top: 80px; 
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2rem;
}

.animated-logo {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    animation: spin 4s linear infinite;
    transition: transform 0.3s ease-in-out;
    flex-shrink: 0;
}

.animated-logo:hover {
    transform: scale(1.1);
}

@keyframes spin {
    0% {
        transform: rotate(0deg);
    }

    100% {
        transform: rotate(360deg);
    }
}

.para {
    font-size: 30px;
    color: #fff;
    text-align: justify;
    max-width: 800px; 
    margin-top: 2rem;
}

.text-container p {
    font-size: 30px;
    color: #fff;
    text-align: center;
}

@media (max-width: 780px) {
    .container {
        flex-direction: column;
        text-align: center;
    }

    .text-container {
        margin-top: 1rem;
    }

    .text-container p {
        font-size: 20px;
    }

    .animated-logo {
        width: 150px;
        height: 150px;
    }

    .para {
        font-size: 15px;
        max-width: 90%;
    }
}
</style>
