<template>
  <div id="app">
  
    <div class="container-fluid">
  
    <section-api/>
    <page-footer/>

    </div>
  </div>
       
</template>

<script>
import SectionApi from './components/SectionApi.vue';

import PageFooter from './components/PageFooter.vue'

export default {
  name: 'App',

  components : {
    SectionApi,
    PageFooter
  }
}
</script>

