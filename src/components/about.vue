<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="row px-5">
    <div class="col-md-4">
      <img class="rounded-circle mr-2 mw-50" src="../assets/ProfilePicture.jpg">
    </div>
    <div class="col-md-8 d-flex">
      <div class="ms-auto d-flex flex-column justify-content-around px-5">
        <p class="lead">Hi i'm Julien! Junior web developper based in Rennes. Just graduated, I continue to practice in order to offer you a fast, safe and ergonomic work. You will find above my deliverables rendered in the context of the Openclassrooms training as well as other personal or professional projects. Specialized in node JS and vue JS, I would be able to realize your back, front or fullstack projects. Check out my latest projects <RouterLink to="/projets">here</RouterLink></p>
        <span class="text-center">icones des languages</span>
      </div>
    </div>
  </div>
  <div class="text-center px-5">
     <div class="divider-custom-line"></div>
    <h3>Mes derniers projets</h3>
     <div class="divider-custom-line"></div>
  <div class="row d-flex justify-content-around mt-3">
    <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="..." alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Groupomania</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'un réseau social d'entreprise, projet FullStack, from scratch.</p>
    <a href="https://github.com/Jdesclos/P7_DesclosJulien_1072021-backend" class="btn btn-primary">GitHub</a>
  </div>
</div>
    <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="..." alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Piiquante</h5>
    <p class="card-text">Projet effectué dans le cadre de la formation OpenClassrooms. Réalisation d'une api pour un site de référencement de sauce piquante.</p>
    <a href="https://github.com/Jdesclos/P6_DesclosJulien_1072021" class="btn btn-primary">GitHub</a>
  </div>
</div>
    <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="..." alt="Card image cap">
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
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
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

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
