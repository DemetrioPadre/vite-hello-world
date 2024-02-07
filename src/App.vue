<!-- creo uno script dove collegare vue e creare ciò che mi serve -->
<script>
import { computed } from 'vue';

export default {
  data() {
    return {
      title: 'primo progetto vite'
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
  <h1>{{ title }}</h1>
</template>

<style></style>
