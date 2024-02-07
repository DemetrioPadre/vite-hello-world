<!-- creo uno script dove collegare vue e creare ciò che mi serve -->
<script>

import AppJumbotron from './components/AppJumbotron.vue';

export default {
  data() {
    return {
      title: 'La mia prima app con Vite',
      secondTitle: 'fino ad ora è stato molto, anzi troppo facile'
    };

  },

  components: {
    AppJumbotron: AppJumbotron,
  }
  // methods: {

  // },
  // computed: {

  // }



};
</script>

<template>
  <!-- dentro il template creo un h1 dove collegare il js -->
  <div class="container">
    <h1 class="blue text-center">{{ title }}</h1>

    <h2 class="red">{{ secondTitle }}</h2>


    <div class="jumboContainer">
      <AppJumbotron class="jumbo"></AppJumbotron>
    </div>


  </div>
</template>


<style>
@import url(./style.css);
</style>
