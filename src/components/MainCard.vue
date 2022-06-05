<template>
<div class="wrapper">
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/PropilePic.png" alt="">
                <h3>Joseph Gill</h3>
                <p>Data Scientist</p>
            </div>
            <div class="social-links">
                <div class="link">
                    <a href="">
                        <img src="../assets/GitHub.png" alt="">
                        <h2>GitHub</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/LinkedIn.png" alt="">
                        <h2>LinkedIn</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/Twitter.png" alt="">
                        <h2>Twitter</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/Instagram.png" alt="">
                        <h2>Instagram</h2>
                    </a>
                </div>
            </div>

        </div>

        <div class="container-two">
            <div class="about-me">
                <h1>About Me</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed auctor tortor.
                    Cras ac facilisis est. Duis sollicitudin vitae sapien ut facilisis. Integer vitae
                    lectus sit amet velit suscipit malesuada. Integer nibh mauris, viverra in tellus nec,
                    euismod ornare augue. Mauris sagittis, odio sollicitudin ullamcorper elementum,
                    dolor elit dignissim lorem, nec egestas ex ante ut tellus. Phasellus enim odio,
                    egestas eu iaculis in, consequat id ipsum. Aliquam erat volutpat. Mauris tempus
                    metus maximus sollicitudin viverra. Vestibulum ante ipsum primis in faucibus orci
                    luctus et ultrices posuere cubilia curae; Nulla facilisi. Aliquam vel pellentesque mi.
                </p>
            </div>
            <div class="technology-section">
                <h1>Technologies Studied</h1>
                <div class="logos">
                    <img src="../assets/Python.png" alt="">
                    <img src="../assets/R.png" alt="">
                    <img src="../assets/Matlab.png" alt="">
                    <img src="../assets/PowerBI.png" alt="">
                    <img src="../assets/Flask.png" alt="">
                </div>
            </div>
            <div class="button-container">
                <div class="projects-button">
                    <a href="">My Projects</a>
                </div>
                <div class="projects-button">
                    <a href="">My Resume</a>
                </div>
            </div>


        </div>

    </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .wrapper{
        display: flex;
        justify-content: center;
    }

    .img{
        height: 50px;
    }

    .main-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        background-color: #A0D4FF;
        border-radius: 25px;
        width: 60%;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .container-one{
        background-color: #1292EE;
        padding: 2.5%;
        width: 30%;
        border-radius: 25px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .profile img{
        height: 5rem;
        border-radius: 50%;
    }

    .link a{
        text-decoration: none;
        color: black;
        font-size: 12px;
    }

    .link img{
        height: 2rem;
    }

    .container-two{
        margin: 2.5%;
        width: 70%;
    }

    .about-me{
        text-align: left;
    }

    .logos img{
        height: 2.5rem;
    }

    .button-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .projects-button {
        background-color: #005CA4;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;
    }

    .projects-button a{
        text-decoration: none;
        color: white
    }

    @media only screen and (max-width: 1020px) {
        .main-container{
            width: 95%;
        }
        
    }

</style>
