<template>
  <div class="fondo_noticias">
    <div class=" row mt-md-5 mt-sm-5 mt-xs-5">
      <div class="  col-lg-6 col-xs-12" v-for="(cat, index) of cats" :key="index">
        <div class=" d-flex justify-content-center aling-items-center">
          <div class=" p-3">
            <img :src="cat.Poster" alt=" cat poster">
          </div>

          <div class=" p-2">
            <div>
              <h3 class="centrar_titulo">
                   {{cat.Title}}
                </h3>
              <hr>
            </div>
            <p class="fondo_parrafo">
              <em> Como no amar a estos seres tan tiernos, que con sus ocurrencia y
              trucos siempre saben sacar una tierna sonrisa, por esto aqui hay
              una pelicula super recomendada con un gato de por medio.</em>

            </p>

          </div>
        </div>

        <div class="d-flex container-fluid justify-content-end pb-2 mt-n2">
          <a
            :href="'https://www.imdb.com/title/' + cat.imdbID"
            class=" btn btn-dark"
          >
            Mas
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import axios from 'axios'

export default {
    name : 'SectionApi',
    data(){
        return{
            cats : null
        }
    },
    mounted(){
        axios 
        .get('http://www.omdbapi.com/?s=cats&type=movie&apikey=838ee1af')
        .then(response =>{
            (this.cats = response.data.Search.slice(0,4))
    
            console.log(this.cats)
            } )
    }
}
</script>

<style scoped>
.fondo_noticias {
    
    background-image: url(https://png.pngtree.com/png-vector/20191027/ourlarge/pngtree-paw-vector-foot-trail-print-of-cat-paw-dog-puppy-cat-png-image_1857057.jpg);
    border: black solid 5px;
    border-radius: 50px;
    border-style:dotted;
}
.centrar_titulo{
    text-align: center;
}
.fondo_parrafo{
    background: white;
}

</style>