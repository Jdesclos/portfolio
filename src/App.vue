<script setup>
import 'bootstrap';
import 'bootstrap/dist/css/bootstrap.min.css';
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="d-flex align-middle mb-5">
    <h1 class="col-md-6">Desclos Julien</h1>
    <nav class="col-md-6 d-flex flex-row-reverse">
      <RouterLink class="col-md-2" to="/projets">Projets</RouterLink>
      <RouterLink class="col-md-2" to="/">About</RouterLink>
    </nav>
  </header>
  <RouterView />
</template>

<style>
@import "@/assets/base.css";
header{
  background-color: #c4e2ca;
  min-height: 5rem;
  padding: 2rem 0rem 2rem 5rem;
}
footer{
  background-color: #c4e2ca;
  min-height: 15rem;
  padding: 2rem 5rem;
}
#app {

  font-weight: normal;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  nav {
    text-align: left;
    font-size: 1rem;
  }
}
</style>
