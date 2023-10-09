<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Fiona Bourgaux</h1>
        <img crossirigin src="1.jpg">
      <p class="lead">
        Votre source fiable d'informations et de ressources en ligne.
      </p>
      <RouterLink to="/about" class="btn btn-primary btn-lg"
        >En savoir plus sur nous</RouterLink
      >
    </div>
  </div>
</template>