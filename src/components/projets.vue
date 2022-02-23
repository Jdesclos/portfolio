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
  <div class="row d-md-flex justify-content-around">
    <div class="card mt-5 mx-auto text-center" style="width: 20rem;">
      <img class="card-img-top img-fluid" src="../assets/icon-above-font.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Groupomania</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'un réseau social d'entreprise, projet FullStack, from scratch.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/P7_DesclosJulien_1072021-backend" class="btn btn-primary">GitHub</a>
  </div>
</div>
    <div class="card mt-5 mx-auto text-center" style="width: 20rem;">
  <img class="card-img-top" src="../assets/16275605596354_PiiquanteLogo.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Piiquante</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'une api pour un site de référencement de sauce piquante.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/P6_DesclosJulien_1072021" class="btn btn-primary">GitHub</a>
  </div>
</div>
    <div class="card mt-5 mx-auto text-center" style="width: 20rem;">
  <img class="card-img-top" src="../assets/15675819263013_image1.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Orinoco</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation du front uniquement en js pour un site de e-commerce.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/DesclosJulien_5_01072021" class="btn btn-primary">GitHub</a>
  </div>
</div>
<div class="card mt-5 mx-auto text-center" style="width: 20rem;">
  <img class="card-img-top" src="../assets/15553465193309_icon-above-font.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">La chouette agence</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Optimisation d'un site déjà existant.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/DesclosJulien_04_01072021" class="btn btn-primary">GitHub</a>
  </div>
</div>
<div class="card mt-5 mx-auto text-center" style="width: 20rem;">
  <img class="card-img-top" src="../assets/ohmyfood@2x.svg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Ho my food</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'animations en css uniquement.</p>
    <a onclick="window.open(this.href); return false" href="https://jdesclos.github.io/DesclosJulien_3_01072021/" class="btn btn-primary">Voir le site</a>
  </div>
</div>
<div class="card mt-5 mx-auto text-center" style="width: 20rem;">
  <img class="card-img-top" src="../assets/Reservia.svg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Reservia</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation du front uniquement en html et css uniquement.</p>
    <a onclick="window.open(this.href); return false" href="https://jdesclos.github.io/DesclosJulien_2_01012021/" class="btn btn-primary">Voir le site</a>
  </div>
</div>
  </div>
</div>
</template>
<style scoped>
.divider-custom-line {
  width: 100%;
  max-width: 7rem;
  height: 0.0;
  background-color: #c4e2ca;
  border-radius: 1rem;
  border-color: #c4e2ca;
  margin: 25px auto;
}
.card-img-top{
  object-fit: contain;
  height: 60%;
}
</style>