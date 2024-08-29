<template>
    <div class="work-container" id="work">
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
            <hr class="horizontal-rule">
            <p class="text-content">Our Work Since 2022</p>
            <p class="text-content">Our Work Since 2022</p>
            <p class="text-content">Our Work Since 2022</p>
            <hr class="horizontal-rule">
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
    </div>
</template>

<style scoped>
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
    animation: move-horizontal 25s linear infinite;
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
    animation: move-horizontal 25s linear infinite;
}

.text-content {
    font-size: 22px;
    margin: 0 20px;
    color: #fff
}

.horizontal-rule {
    border: 0;
    border-top: 2px solid #fff;
    width: 100%;
    flex: 1;
    margin: 0 20px;
}
</style>
