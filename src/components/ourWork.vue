<template>
    <div class="work-container" data-aos="fade-up" id="work">
        <p class="heading">Our Work</p>
        <div class="image-row">
            <img src="../assets/images/work/1.jpg">
            <img src="../assets/images/work/2.jpg">
            <img src="../assets/images/work/3.jpg">
            <img src="../assets/images/work/4.jpg">
            <img src="../assets/images/work/5.jpg">
            <img src="../assets/images/work/6.jpg">
            <img src="../assets/images/work/7.jpg">
            <img src="../assets/images/work/8.jpg">
            <img src="../assets/images/work/9.jpg">
        </div>
        <div class="text-row">
            <p class="text-content">Our Work Since 2022</p>
        </div>
        <div class="image-row">
            <img src="../assets/images/work/10.jpg">
            <img src="../assets/images/work/11.jpg">
            <img src="../assets/images/work/12.jpg">
            <img src="../assets/images/work/13.jpg">
            <img src="../assets/images/work/14.jpg">
            <img src="../assets/images/work/15.jpg">
            <img src="../assets/images/work/16.jpg">
            <img src="../assets/images/work/17.jpg">
            <img src="../assets/images/work/18.jpg">
            <img src="../assets/images/work/19.jpg">
        </div>
        <div class="mt-5 mb-5 cta-section">
            <p class="cta-text">What Are You Waiting for ?</p>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSdBP0wPUzTa81DN3zOmaxkQ6AxibAyssnWztcPnVV1g0NwT7A/viewform?fbclid=IwY2xjawE9zwtleHRuA2FlbQIxMAABHdlvEC4nCp4dZmFdeNAqgYufeVVtheRjrikI-LUUtfRlx3kmq3WKdOZYnw_aem_YIuBoVNMkscLlbI-nI_V9A"
                target="_blank">
                <button class="cta-button">Join Us From Here</button>
            </a>
        </div>
    </div>
</template>

<style scoped>
.cta-section {
    text-align: center;
}

.cta-text {
    font-size: 26px;
    font-weight: bold;
    color: blue;
    margin-bottom: 20px;
}

.cta-button {
    background-color: white;
    color: #007BFF;
    border: none;
    padding: 15px 30px;
    font-size: 18px;
    border-radius: 5px;
    transition: all 0.3s ease;
    cursor: pointer;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
}

.cta-button:hover {
    color: white;
    transform: translateY(-3px);
    background-color: blue;
}

.work-container {
    display: flex;
    overflow: hidden;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.heading {
    margin-bottom: 20px;
    font-size: 30px;
    color: blue;
    font-weight: bold;
}

@keyframes move-horizontal {
    0% {
        transform: translateX(100%);
    }

    100% {
        transform: translateX(-100%);
    }
}

.image-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
    animation: move-horizontal 18s linear infinite;
}

.image-row img {
    height: 120px;
    margin-right: 20px;
}

.text-row {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-bottom: 20px;
    animation: move-horizontal 18s linear infinite;
}

.text-content {
    font-size: 22px;
    margin: 0 20px;
    color: #fff
}


</style>
