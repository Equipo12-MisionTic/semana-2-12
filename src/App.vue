<template>
  <div id="app">


        <div class="container-fluid">
        <div class="row justify-content-center mb-5">
          <team-card></team-card>
        </div>
        </div>
  </div>
</template>

<script>
import { component } from 'vue/types/umd'
import TeamCard from './components/TeamCard.vue'
import TeamCard from '/components/TeamCard.vue'


export default {
  name: 'App',
  components : {
    TeamCard
  },

  data(){
    return{
      members : [
        {
​          codigo​: ​1​,
​          nombre​: ​'Lucas Mera'​,
​          descripcion​: ​'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris condimentum ac elit et accumsan.'​,
​          rol​: ​'Desarrollador backend'​,
​          image​: ​'https://placeimg.com/192/192/people' 
        },
        {​ 
          codigo​: ​2​,
​          nombre​: ​'Lucas Mera'​,
​          descripcion​: ​'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris condimentum ac elit et accumsan.'​,
​           rol​: ​'Desarrollador backend'​,
​           image​: ​'https://placeimg.com/192/192/people' 
        },
        {​ 
          codigo​: ​3​,
​          nombre​: ​'Lucas Mera'​,
​          descripcion​: ​'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris condimentum ac elit et accumsan.'​,
​           rol​: ​'Desarrollador backend'​,
​           image​: ​'https://placeimg.com/192/192/people' 
        },
        {​ 
          codigo​: ​4,
​          nombre​: ​'Lucas Mera'​,
​          descripcion​: ​'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris condimentum ac elit et accumsan.'​,
​           rol​: ​'Desarrollador backend'​,
​           image​: ​'https://placeimg.com/192/192/people' 
        },
        {​ 
          codigo​: ​5,
​          nombre​: ​'Lucas Mera'​,
​          descripcion​: ​'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris condimentum ac elit et accumsan.'​,
​           rol​: ​'Desarrollador backend'​,
​           image​: ​'https://placeimg.com/192/192/people' 
        },
      ],
    }
  }
  
</script>