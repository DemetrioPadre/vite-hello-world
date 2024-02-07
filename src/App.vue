<!-- creo uno script dove collegare vue e creare ciò che mi serve -->
<script>


export default {
  data() {
    return {
      title: 'La mia prima app con Vite',
      secondTitle: 'fino ad ora è stato molto, anzi troppo facile'
    };

  },
  methods: {

  },
  computed: {

  }



};
</script>

<template>
  <!-- dentro il template creo un h1 dove collegare il js -->
  <div>
    <h1 class="blue">{{ title }}</h1>
  </div>
  <div>
    <h2 class="red">{{ secondTitle }}</h2>
  </div>
</template>


<style>
@import url(./style.css);
</style>
