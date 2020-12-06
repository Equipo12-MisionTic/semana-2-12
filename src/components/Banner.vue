<template>

    <div>
    <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark">
      <a class="navbar-brand" href="# ">
        <img
          src="../assets/logo.jpg"
          width="30 "
          height="30"
          class="d-inline-block align-top"
          alt="bootstrap"
          loading="lazy "
        />
        CATS.MEOW
      </a>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav ">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">Noticias<span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="# ">Equipo</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="# ">Contacto</a>
          </li>
        </ul>
      </div>
    </nav>
    <!-- PRIMERA PARTE ARRIBA DEL CARROUSEL -->
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      data-ride="carousel">
      <ol class="carousel-indicators">
        <li
          data-target="#carouselExampleCaptions"
          data-slide-to="0"
          class="active"
        ></li>
        <li
          data-target="#carouselExampleCaptions"
          data-slide-to="1"
          class=""
        ></li>
        <li
          data-target="#carouselExampleCaptions"
          data-slide-to="2"
          class=""
        ></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <a href="https://es.wikipedia.org/wiki/Sphynx">
            <img src="../assets/gato1.jpg" alt="gato1" height="500" width="1300" />
          </a>
          <svg
            class="bd-placeholder-img bd-placeholder-img-lg d-block w-100"
            width="50"
            height="120"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="xMidYMid slice"
            focusable="false"
            role="img"
            aria-label="Placeholder: First slide"
          >
            <title>Placeholder</title>
            <rect width="100%" height="100%" fill="#777"></rect>
            <text x="50%" y="50%" fill="#555" dy=".3em"></text>
          </svg>
          <div class="carousel-caption d-none d-md-block">
            <h5>Sphynx</h5>
            <p>
              Su característica más llamativa es la
              aparente ausencia de pelaje y su aspecto delgado y esbelto.
            </p>
          </div>
        </div>
        <!-- ARRIBA PRIMERA -FOTO- FOTO DE CARROUSEL -->
        <div class="carousel-item">
          <a href="https://es.wikipedia.org/wiki/Maine_Coon">
            <img src="../assets/gato4.jpg" alt="gato4" height="500" width="1400" />
          </a>
          <svg
            class="bd-placeholder-img bd-placeholder-img-lg d-block w-100"
            width="800"
            height="120"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="xMidYMid slice"
            focusable="false"
            role="img"
            aria-label="Placeholder: Second slide"
          >
            <title>Placeholder</title>
            <rect width="100%" height="100%" fill="#666"></rect>
            <text x="50%" y="50%" fill="#444" dy=".3em"></text>
          </svg>
          <div class="carousel-caption d-none d-md-block">
            <h5>Maine Coon</h5>
            <p>
              El Maine Coon es conocida por ser la raza de gato doméstico más
              grande del mundo.
            </p>
          </div>
        </div>
        <!-- ARRIBA SEGUNDA -FOTO- PARTE DEL CARROUSEL-->
        <div class="carousel-item">
          <a href="https://es.wikipedia.org/wiki/Munchkin_(gato)">
            <img src="../assets/gato2.jpg" alt="gato2" height="500" width="1400" />
          </a>
          <svg
            class="bd-placeholder-img bd-placeholder-img-lg d-block w-100"
            idth="800"
            height="120"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="xMidYMid slice"
            focusable="false"
            role="img"
            aria-label="Placeholder: Third slide"
          >
            <title>Placeholder</title>
            <rect width="100%" height="100%" fill="#555"></rect>
            <text x="50%" y="50%" fill="#333" dy=".3em"></text>
          </svg>
          <div class="carousel-caption d-none d-md-block">
            <h5>Munchkin</h5>
            <p>
              Es un gato de tamaño mediano con las patas más cortas de lo
              normal, como si de un perro salchicha se tratara.
            </p>
          </div>
        </div>
        <!-- ARRIBA TERCERA -FOTO- PARTE DEL CARROUSEL-->
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleCaptions"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleCaptions"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>            


