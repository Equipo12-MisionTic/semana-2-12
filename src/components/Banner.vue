<template>
 
<body>  
    <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark ">
        <a class="navbar-brand " href="# ">
        <img src="https://getbootstrap.com/docs/4.5/assets/brand/bootstrap-solid.svg "
       width="30 " height="30
        " class="d-inline-block align-top " alt=" " loading="lazy "> Bootstrap
        </a>
        <div class="collapse navbar-collapse justify-content-end " id="navbarNav ">
        <ul class="navbar-nav ">
        <li class="nav-item active ">
        <a class="nav-link " href="# ">Noticias<span class="sr-only
       ">(current)</span></a>
        </li>
        <li class="nav-item ">
        <a class="nav-link " href="# ">Equipo</a>
        </li>
        <li class="nav-item ">
        <a class="nav-link " href="# ">Contacto</a>
        </li>
        <li class="nav-item ">
        <a class="nav-link disabled " href="# " tabindex="-1 " ariadisabled="true ">Disabled</a>
        </li>
        </ul>
        </div>
        </nav>
        <!-- PRIMERA PARTE ARRIBA DEL CARROUSEL --> 
        <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
            <li data-target="#carouselExampleCaptions" data-slide-to="0"
        class="active"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="1" class=""></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="2" class=""></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <a href="https://es.wikipedia.org/wiki/Sphynx">
                        <img src="gato1.jpg" alt="" height="500" width="2000">
                    </a>
                    <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="50" height="120" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                    aria-label="Placeholder: First slide"><title>Placeholder</title>
                    <rect
                        width="100%" height="100%" fill="#777"></rect><text x="50%" y="50%" fill="#555" dy=".3em"></text></svg>
            <div class="carousel-caption d-none d-md-block">
                <h5>Sphynx</h5>
                <p>Es una raza de gato cuya característica más llamativa es la aparente ausencia de pelaje y su aspecto delgado y esbelto.</p>
                </div>
            </div>
            <!-- ARRIBA PRIMERA -FOTO- FOTO DE CARROUSEL --> 
            <div class="carousel-item">
                <a href="https://es.wikipedia.org/wiki/Maine_Coon">
                    <img src="gato4.jpg" alt="" height="500" width="2000">
                </a>
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="120" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                aria-label="Placeholder: Second slide"><title>Placeholder</title>
                <rect
                    width="100%" height="100%" fill="#666"></rect><text x="50%" y="50%" fill="#444" dy=".3em"></text></svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Maine Coon</h5>
                    <p>El Maine Coon es conocida por ser la raza de gato doméstico más grande del mundo.</p>
            </div>
            </div>
            <!-- ARRIBA SEGUNDA -FOTO- PARTE DEL CARROUSEL--> 
            <div class="carousel-item">
                <a href="https://es.wikipedia.org/wiki/Munchkin_(gato)">
                    <img src="gato2.jpg" alt="" height="500" width="2000">
                </a>
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" idth="800" height="120" xmlns="http://www.w3.org/2000/svg"  preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                    aria-label="Placeholder: Third slide"><title>Placeholder</title>
                <rect
                width="100%" height="100%" fill="#555"></rect><text x="50%" y="50%" fill="#333" dy=".3em"></text></svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Munchkin</h5>
                    <p>Es un gato de tamaño mediano con las patas más cortas de lo normal, como si de un perro salchicha se tratara.</p>
                        </div>
                    </div>
            <!-- ARRIBA TERCERA -FOTO- PARTE DEL CARROUSEL--> 
            </div>
            <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
            </div>
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
        <!--STARTER TEMPLATE DE BOOTSTRAP--> 
        
         <div id="app">
        </div>
</body>
</template>

<script>
export default {
    name: 'Banner',
}
</script>            


