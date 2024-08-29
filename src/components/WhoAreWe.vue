<template>
    <div class="about-section container mb-5" id="who">
        <p class="title" data-aos="fade-up">Who Are We</p>
        <div class="content d-flex">
            <div class="image-container" data-aos="fade-up">
                <img src="../assets/images/contest.jpg" alt="Competitive Programming Club">
            </div>
            <div class="text-container" data-aos="fade-up">
                Our Competitive Programming Club at Enicarthage, founded in 2022, aims to maximize the skills of
                students in this growing field. Through practical workshops and challenging contests, we provide our
                members with the opportunity to enhance their programming abilities, solve complex problems, and prepare
                for national and international competitions. The club is a space for learning, sharing, and excellence,
                open to anyone eager to improve their skills and take on exciting challenges.
            </div>
        </div>
        <div class="members-section text-center" data-aos="fade-up">
            <p class="members-title">Our Members</p>
            <p class="members-count">
                <AnimatedCounter :value="40" :duration="3000" />
            </p>
            <p class="members-date">As of November 2023</p>
        </div>
        <div class="text-center" data-aos="fade-up">
            <p class="members-title mb-5">Team</p>
            <div class="row justify-content-center">
                <div class="container_box col-lg-4 mb-3" data-aos="fade-up" data-aos-delay="100">
                    <div class="card_box">
                        <img src="../assets/images/team/456904703_487293680610157_10408931192533386_n.jpg" alt="">
                    </div>
                    <div class="content_box">
                        <h3 style="color:#4fc3dc">Mohamed bouafif</h3>
                        <div class="all_link">
                            <a class=" mx-2" href="#!"><i class="fa-brands fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
                <div class="container_box col-lg-4 mb-4" data-aos="fade-up" data-aos-delay="200">
                    <div class="card_box">
                        <img src="../assets/images/team/456460250_487293647276827_4341405322816089477_n.jpg" alt="">
                    </div>
                    <div class="content_box">
                        <h3 style="color:#4fc3dc">Rochdi fridhi</h3>
                        <div class="all_link">
                            <a class=" mx-2" href="#!"><i class="fa-brands fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
                <div class="container_box col-lg-4 mb-3" data-aos="fade-up" data-aos-delay="300">
                    <div class="card_box">
                        <img src="../assets/images/team/456755173_487293667276825_1083864908460527710_n.jpg" alt="">
                    </div>
                    <div class="content_box">
                        <h3 style="color:#4fc3dc">Mariem Charef</h3>
                        <div class="all_link">
                            <a class=" mx-2" href="#!"><i class="fa-brands fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
                <div class="container_box col-lg-4 mb-3" data-aos="fade-up" data-aos-delay="400">
                    <div class="card_box">
                        <img src="../assets/images/team/456603958_487294090610116_3468557199274106726_n.jpg" alt="">
                    </div>
                    <div class="content_box">
                        <h3 style="color:#4fc3dc">Sabrine Kamkoum</h3>
                        <div class="all_link">
                            <a class=" mx-2" href="#!"><i class="fa-brands fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
                <div class="container_box col-lg-4" data-aos="fade-up" data-aos-delay="500">
                    <div class="card_box">
                        <img src="../assets/images/team/456961274_487294067276785_6696629118101263682_n.jpg" alt="">
                    </div>
                    <div class="content_box">
                        <h3 style="color:#4fc3dc">Arij Souissi</h3>
                        <div class="all_link">
                            <a class=" mx-2" href="#!"><i class="fa-brands fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
                <div class="container_box col-lg-4 mb-3" data-aos="fade-up" data-aos-delay="600">
                    <div class="card_box">
                        <img src="../assets/images/team/456557243_487294050610120_6619695722693227833_n.jpg" alt="">
                    </div>
                    <div class="content_box">
                        <h3 style="color:#4fc3dc">Talel Mejri</h3>
                        <div class="all_link">
                            <a class=" mx-2" href="#!"><i class="fa-brands fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import AnimatedCounter from "vue-animated-counter"
export default {
    components: {
        AnimatedCounter
    }
};
</script>

<style scoped>
.title {
    font-size: 30px;
    font-weight: bold;
    color: #2a3eb1;
    text-align: center;
    margin-bottom: 20px;
}

.content {
    display: flex;
    align-items: center;
    gap: 30px;
}

.image-container {
    flex: 1;
}

.image-container img {
    width: 100%;
    max-width: 400px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.text-container {
    flex: 2;
    font-size: 20px;
    line-height: 1.6;
    color: #fff;
}

@media (max-width: 780px) {
    .content {
        flex-direction: column;
        text-align: center;
    }

    .image-container img {
        max-width: 100%;
        margin-bottom: 20px;
    }

    .text-container {
        font-size: 15px;
    }
}

.members-section {
    padding: 40px 20px;
    border-radius: 12px;
    max-width: 400px;
    margin: 0 auto;
}

.members-title {
    font-size: 32px;
    font-weight: 700;
    color: #2a3eb1;
    margin-bottom: 10px;
}

.members-count {
    font-size: 48px;
    font-weight: 700;
    color: #fff;
    margin-bottom: 5px;
}

.members-date {
    font-size: 18px;
    color: #777;
}

.container_box {
    width: 200px !important;
    height: 190px;
    margin: 0px 70px;
    background: linear-gradient(60deg, #000, #434343);
    border-radius: 20%;
    box-shadow: rgba(0, 0, 0, .7) 0px 4px 12px;
}

.container_box .card_box {
    width: 200px;
    height: 190px;
    z-index: 1;
    margin: 0 auto;
    position: relative;
    border-radius: 20%;
    transition: 1s;
}

.card_box img {
    width: 100%;
    height: 100%;
    border-radius: 20%;
    margin-left: -10px;
}

.container_box .content_box {
    width: 100%;
    height: 100%;
    border-radius: 10px;
    transform: translateY(-168px);
    transition: 1s;
}

.container_box .content_box h3,
.container_box .content_box p {
    text-align: center;
    color: #000;
    font-weight: 600;
}

.container_box .content_box h3 {
    font-size: 18px;
    text-transform: uppercase;
    color: #fff;
    padding-top: 12px;
}

.container_box .content_box p {
    margin-top: -15px;
    font-family: monospace;
}

.container_box:hover .card_box {
    width: 60%;
    height: 70%;
    opacity: 1;
    transform: translateY(-40px);
}

.container_box:hover .content_box {
    transform: translateY(-40px);
}

.container_box .all_link {
    text-align: center;
}

.container_box .all_link a {
    color: #fff !important;
}

.container_box .all_link :hover {
    color: #b50edf;
    transition: 0.3s;
}
</style>
