<script setup>
import 'bootstrap';
import 'bootstrap/dist/css/bootstrap.min.css';

import { RouterLink, RouterView } from "vue-router";

</script>

<template>
  <header class="d-md-flex align-middle mb-5">
    <h1 class="col-md-4 fs-1"><RouterLink to="/">Desclos Julien</RouterLink></h1>
    <nav class="d-md-flex col-md-8 fs-1 flex-row-reverse">
      <RouterLink class="mx-3 fs-1" to="/projets">Projets</RouterLink>
      <RouterLink class="mx-3 fs-1" to="/">About</RouterLink>
      <p><a class="mx-3 fs-1" href="mailto:desclos.julien@gmail.com">Email</a></p>
      <p id="thumwrap"><a @click="displayCv()" class="mx-3 fs-1 thumb" href="#" alt="Télécharger mon cv">Mon cv</a></p>
      <p><a onclick="window.open(this.href); return false" class="mx-3 fs-1" href="https://www.linkedin.com/in/julien-desclos-2a5486204/">Linkedin</a></p>
    </nav>
  </header>
  <div id="cv" class="d-flex justify-content-center" v-if="show" ><a href="src/assets/cv_Dev_web_Desclos_Julien.pdf" download alt="Télécharger mon cv"><img class="cvImg" title="Télécharger le cv" src="./assets/cv_dev_web_Desclos_Julien.png"></a> <button @click="displayCv()" class="btn-cross" >X</button></div>
  <RouterView />
</template>
<script>
export default {
  data() {
    return {
      show: false,
  };
  },
  methods: {
    displayCv() {
      if(this.show != true){
        this.show = true;
      }else{
        this.show = false;
      }
    },
  },
}
</script>
<style>
@import "@/assets/base.css";
header {
  background-color: #c4e2ca;
  min-height: 5rem;
  padding: 2rem 0rem 2rem 5rem;
}
header a {
  color: #3583ca;
}
@media (max-width: 767.98px) {
  header{
    text-align: center;
    padding: 0px;
  }
}
footer{
  background-color: #c4e2ca;
  min-height: 15rem;
  padding: 2rem 5rem;
}
#app {

  font-weight: normal;
}
p{
  font-size: 1.25rem;
}
.logo {
  display: block;
  margin: 0 auto 2rem;
}
#cv {
  text-align: center;
}
#cv img {
  max-width: 45rem;
  max-height: 55rem;
  object-fit: contain;
}
a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

nav {
  width: 100%;
  text-align: center;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
  text-decoration: underline;
  transform: scale(1.2);
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

a:hover {
  text-decoration: underline;
  transform: scale(1.2);
}
.cvImg:hover{
transform: scale(1.1);
transition-duration: 1000;
}
.btn-cross{
  height: 25px;
  width: 20px;
  padding: 0px;
  border: none;
  background-color: white;
  color: red;
  font-size: 2rem;
}
</style>
