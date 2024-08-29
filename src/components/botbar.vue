<template>
    <div>
        <nav class="bot-bar">
            <div class="bot-bar-center">
                <ul>
                    <li>
                        <a href="https://www.facebook.com/talel.mejri.140/" target="_blank" rel="noopener noreferrer"
                            class="link">
                            <i class="fa-brands fa-facebook mx-2"></i>
                            <span class="text">Facebook</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.youtube.com/channel/UCH3d1NuLBfPiE0IOXoz3upA" target="_blank"
                            rel="noopener noreferrer" class="link">
                            <i class="fa-brands fa-instagram mx-2"></i>
                            <span class="text">Instagram</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.linkedin.com/in/talel-mejri-899a73232/" target="_blank"
                            rel="noopener noreferrer" class="link">
                            <i class="fa-brands fa-linkedin mx-2"></i>
                            <span class="text">LinkedIn</span>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>
<style scoped>
.bot-bar {
    display: flex;
    align-items: center;
    background: rgba(0, 0, 60, 0.3);
    padding: 0;
    margin-right: 5rem;
    position: fixed;
    right: 0;
    bottom: 0;
    z-index: 1000;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(10px);
}

.bot-bar:hover {
    background: rgba(0, 0, 50, .9);
}

.bot-bar-center {
    padding: 1rem;
    flex: 1;
    display: flex;
    justify-content: center;
}

.bot-bar-center ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 0;
    padding: 0;
}

.bot-bar-center ul li {
    margin: 0 1rem;
}

.bot-bar-center ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;

    transition: color 0.3s ease;
}

.bot-bar-center ul li a:hover {
    color: blue;
}


@media (max-width: 768px) {
    .bot-bar {
        margin-right: 0;
        flex-direction: column;
        align-items: center;
    }

    .bot-bar-center ul {
        flex-direction: column;
        align-items: center;
    }

    .bot-bar-center ul li {
        margin: 0.5rem 0;
    }

    .bot-bar-right {
        justify-content: center;
        margin-top: 1rem;
    }

    .link .text {
        display: none;
    }
}
</style>