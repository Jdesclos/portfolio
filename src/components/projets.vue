<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
<div class="divider-custom-line"></div>
  <div class="container">
  <div class="row d-flex justify-content-around">
    <div class="card" style="width: 18rem;">
      <img class="card-img-top" src="" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Groupomania</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'un réseau social d'entreprise, projet FullStack, from scratch.</p>
    <a href="https://github.com/Jdesclos/P7_DesclosJulien_1072021-backend" class="btn btn-primary">GitHub</a>
  </div>
</div>
    <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Piiquante</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'une api pour un site de référencement de sauce piquante.</p>
    <a href="https://github.com/Jdesclos/P6_DesclosJulien_1072021" class="btn btn-primary">GitHub</a>
  </div>
</div>
    <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Orinoco</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation du front uniquement en js pour un site de e-commerce.</p>
    <a href="https://github.com/Jdesclos/DesclosJulien_5_01072021" class="btn btn-primary">GitHub</a>
  </div>
</div>
  </div>
</div>
</template>
<style scoped>
.divider-custom-line {
  width: 100%;
  max-width: 7rem;
  height: 0.25rem;
  background-color: #c4e2ca;
  border-radius: 1rem;
  border-color: #c4e2ca;
  margin: 25px auto;
}
</style>