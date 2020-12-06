<template>
  <div id="app">

    <div class="container-fluid">
    <Banner></Banner>
    <section-api/>
    <div class="container-fluid">
      <div class="row justify-content-center mb-5">
        <div class="col mt-5" v-for="(item, index) of team " :key="index">
          <team-card v-bind:member="item"> </team-card>
        </div>
        </div>
  </div>
    
    <page-footer/>

    </div>
  </div>
       
</template>

<script>

import SectionApi from './components/SectionApi.vue';
import Banner from './components/Banner.vue'
import PageFooter from './components/PageFooter.vue'
import TeamCard from './components/TeamCard.vue';

export default {
  name: 'App',

  components : {
    SectionApi,
    PageFooter,
    Banner,
    TeamCard,
  },

  data()
{
  
  return {
    team: [
      {
        codigo: 1,
        nombre: "Vanessa Aguado",
        descripcion: "Soy profesional en negocios internacionales. Me encantan los gatos.",
        rol: "Analista, arquitecta y tester de software",
        imagen: require("./assets/vanessa.jpg")

      },
      {
        codigo: 2,
        nombre: "Alvaro Peralta",
        descripcion: "Tengo 28 años, soy programador, me gustan los gatos porque no invaden mi espacio personal como los perros.",
        rol: "Frontend developer",
        imagen: require("./assets/alvaro.jpg")

      },
      {
        codigo: 3,
        nombre: "Sergio Pineda",
        descripcion: "Tengo 21 años y soy estudiante de odontología, prefiero los perros pero no me disgustan los gatos muy cariñosos.",
        rol: "Frontend developer",
        imagen: require("./assets/sergio.jpg")

      },
      {
        codigo: 4,
        nombre: "Juan Villegas",
        descripcion: " Aficionado por la tecnología, los viajes al pueblo y amante del desarrollo. Me gustan los gatos esfinges ya que soy alérgico al pelo de los mismos",
        rol: "Backend Developer",
        imagen: require("./assets/juan.jpg")

      },
      {
        codigo: 5,
        nombre: "Diego Garzon",
        descripcion: "Soy estudiante de Ingeniería Catastral y Geodesia, prefiero los gatos como pelusa porque me recuerda a mi película favorita",
        rol: "Backend Developer",
        imagen: require("./assets/diego.jpg")

      },
    ]
  }
}

}


</script>

