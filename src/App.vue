<template>
  <div id="app">
    <div class="container-fluid">
    <div class="row justify-content-center mb-5">
      <div class="col mt-5" v-for="(item, index) of members" :key="index">
        <team-card v-bind:member="item"></team-card>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
import { component } from 'vue/types/umd'
import TeamCard from './components/TeamCard.vue'


export default {
  name: 'App',

  components : {
    TeamCard
  },

  data(){
    return{
      title: 'Prueba que Vue funciona',
      members: [
         {
​          codigo​: ​1​,
​          nombre​: ​'Vanessa Aguado'​,
​          descripcion​: ​'Tengo 26 años, soy profesional en negocios internacionales.'​,
​          rol​: ​'Analista de software, arquitecto de software y tester.'​,
​          image​: ​'./img/1.jpg' 
        },
        {​ 
          codigo​: ​2​,
​          nombre​: ​'Álvaro Peralta'​,
​          descripcion​: ​'Tengo 28 años, soy programador.'​,
​           rol​: ​'Desarrollador frontend'​,
​           image​: ​'./img/2.jpg'
        },
        {​ 
          codigo​: ​3​,
​          nombre​: ​'Sergio Pineda'​,
​          descripcion​: ​'Tengo 21 años, soy estudiante de Odontología.'​,
​           rol​: ​'Desarrollador frontend'​,
​           image​: ​'./img/3.jpg'
        },
        {​ 
          codigo​: ​4,
​          nombre​: ​'Juan Villegas'​,
​          descripcion​: ​'Aficionado por la teconología y nuevo amante del desarrollo.'​,
​           rol​: ​'Desarrollador backend'​,
​           image​: './img/4.jpg'
        },
        {​ 
          codigo​: ​5,
​          nombre​: ​'Diego Garzón'​,
​          descripcion​: ​' Soy estudiante de Ingeniería Catastral y Geodesia.'​,
​           rol​: ​'Desarrollador frontend'​,
​           image​: ​'./img/5.jpg' 
        }
      ],
    }
  }
}
</script>