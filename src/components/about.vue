<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="container-xxl d-md-flex px-5">
    <div class="col-md-4 text-center">
      <img class="rounded-circle mr-2 mw-50" src="../assets/ProfilePicture.jpg">
    </div>
    <!-- <div class="col-md-8 d-flex">
      <div class="ms-auto d-flex flex-column justify-content-around px-5">
        <p class="lead">Hi i'm Julien! Junior web developper based in Rennes. Just graduated, I continue to practice in order to offer you a fast, safe and ergonomic work. You will find above my deliverables rendered in the context of the Openclassrooms training as well as other personal or professional projects. Specialized in node JS and vue JS, I would be able to realize your back, front or fullstack projects. Check out my latest projects <RouterLink to="/projets">here.</RouterLink></p>
        <span class="text-center">icones des languages</span>
      </div>
    </div>
  </div> -->
  <div class="col-md-8 d-md-flex">
      <div class="ms-auto d-flex flex-column justify-content-around px-5 w-80">
        <p class="lead fs-3"><span class="fs-1">Bonjour</span>,<br> je m'appelle Julien ! Développeur web junior basé à Rennes. Tout juste diplômé, je continue à pratiquer afin de vous proposer un travail rapide, sûr et ergonomique. Vous trouverez ci-dessus mes livrables rendus dans le cadre de la formation Openclassrooms ainsi que d'autres projets personnels ou professionnels. Spécialisé en node JS et vue JS, je serais en mesure de réaliser vos projets back, front ou fullstack. Consultez mes derniers projets <RouterLink to="/projets">ici.</RouterLink></p>
        <span class="text-center"><font-awesome-icon icon="fa-brands fa-vuejs" /> <font-awesome-icon icon="fa-brands fa-bootstrap" /></span>
      </div>
    </div>
  </div>
  <div class="text-center px-5">
     <div class="divider-custom-line"></div>
    <h3 class="fs-1">Mes derniers projets</h3>
     <div class="divider-custom-line"></div>
  </div>
<div class="d-md-flex justify-content-between">
  <div class="card mx-5 mt-5 text-center" >
      <img class="card-img-top img-fluid" src="../assets/icon-above-font.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title fs-2">Groupomania</h5>
    <p class="card-text fs-3">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'un réseau social d'entreprise, projet FullStack, from scratch.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/P7_DesclosJulien_1072021-backend" class="btn btn-primary fs-3">GitHub</a>
  </div>
</div>
    <div class="card mx-5 mt-5 text-center" >
  <img class="card-img-top" src="../assets/16275605596354_PiiquanteLogo.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title fs-2">Piiquante</h5>
    <p class="card-text fs-3">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'une api pour un site de référencement de sauce piquante.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/P6_DesclosJulien_1072021" class="btn btn-primary fs-3">GitHub</a>
  </div>
</div>
     <div class="card mx-5 mt-5 text-center" >
  <img class="card-img-top" src="../assets/15675819263013_image1.png" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title fs-2">Orinoco</h5>
    <p class="card-text fs-3">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation du front uniquement en js pour un site de e-commerce.</p>
    <a onclick="window.open(this.href); return false" href="https://github.com/Jdesclos/DesclosJulien_5_01072021" class="btn btn-primary fs-3">GitHub</a>
  </div>
</div>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}
.card-img-top{
  object-fit: contain;
  height: 60%;
}
h3 {
  font-size: 1.2rem;
}
.rounded-circle{
  max-width: 65%;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}
.divider-custom-line {
  width: 100%;
  max-width: 7rem;
  height: 0.25rem;
  background-color: #c4e2ca;
  border-radius: 1rem;
  border-color: #c4e2ca;
  margin: 25px auto;
}
.container-xxl{
  max-width: 3000px;
}
@media (max-width: 767.98px) {
 .container-xxl{
   padding: 0 !important;
 }
}
</style>
