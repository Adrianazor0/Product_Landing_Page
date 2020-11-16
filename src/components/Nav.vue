<template>
  
  <header>
        <nav id="nav1" class="navbar navbar-info">
            <img class="img-fluid" src="imágenes/logo-nzxt-black.png" alt="Logo de nzxt">
            <ul class="nav justify-content-end">
                <li class="nav-item">
                    <a class="nav-link text-info active" href="#"><small>LOG IN</small></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-info" href="#"><small>SIGN UP</small></a>
                </li>
            </ul>
        </nav>
        <nav id="nav2" class="navbar navbar-expand-lg navbar-dark">
            <a class="navbar-brand" href="#"><img class="img-fluid navLogo" src="imágenes/logo-white.png" alt="logo de bld"></a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">WHAT IS BLD<span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="#">CUSTOMER REVIEWS</a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="#">SUPPORT</a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="#">FAQ</a>
                    </li>

                </ul>
                <button id="btnNav" class="btn btn-outline-light my-2 my-sm-0" type="submit">GET STARTED</button>
            </div>
        </nav>
    </header>
        
</template>

<script>
export default {
  name: "Nav"
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>


</style>
