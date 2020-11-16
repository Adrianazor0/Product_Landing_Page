<template>
  <section id="footer">
            <form action="#">
                <div class="form-group mx-auto text-light">
                    <h2>STAY <well>IN TOUCH</well></h2>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Your Email Address">
                </div>
            </form>
            <div class="row">
                <div id="leftSide" class="col-sm d-flex justify-content-start align-items-end">
                    <img src="imágenes/logo-nzxt.png" class="img-fluid"/> <cite>2018. All Rights Are Reserved.</cite>
                </div>
                <div id="centeredOne" class="col-sm d-flex justify-content-center align-items-end">
                    <a href="#">Privacy Policy</a> 
                    <a href="#">Terms of Service</a> 
                    <img src="imágenes/eeuu_band.jpg" class="img-fluid"/><div class="btn-group dropup">
                        <button id="languageBtn" type="button" class="btn btn-outline-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                          English
                        </button>
                        <div class="dropdown-menu">
                            <button class="dropdown-item" type="button">French</button>
                            <button class="dropdown-item" type="button">Spanish</button>
                        </div>
                      </div>
                </div>
                <div id="rightSide" class="col-sm d-flex justify-content-end align-items-end">
                    <a href="www.facebook.com"><i class="fab fa-facebook-square"></i></a>
                    <a href="www.twitter.com"><i class="fab fa-twitter"></i></a>
                    <a href="www.instagram.com"><i class="fab fa-instagram"></i></a>
                    <a href="www.youtube.com"><i class="fab fa-youtube"></i></a>
                    <a href="www.twitch.com"><i class="fab fa-twitch"></i></a>
                    <a href="www.steam.com"><i class="fab fa-steam-symbol"></i></a>
                    <a href="www.github.com"><i class="fab fa-github"></i></a>
                    <a href="www.discord.com"><i class="fab fa-discord"></i></a>
                </div>
            </div>
        </section>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss">

</style>