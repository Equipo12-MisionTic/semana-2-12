

<template>
  
    
          <div class=" card text-white bg-dark">
            <div class="d-flex justify-content-center p-2">
              <img v-bind:src="member.imagen" alt="imagen del miembro">
            </div>
            <div class="card-body">
              <h3 class="card-title">{{member.nombre}}</h3>
              <p class="card-text"> Código:{{ member.codigo}}</p>
              <p class="card-text">{{ member.descripcion}}</p>
              <p class="card-text"> Rol:{{ member.rol}}</p>
              
            </div>
            <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
            </div>
          </div>
    
    
</template>

<script>
export default {
  name: "TeamCard",
  props: ["member"],
};
</script>

<style scoped>
 
</style>
