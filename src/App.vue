<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Card from './components/card.vue'
import './Principal.css'
import './bootstrap.min.css'
import './animate.min.css'

</script>

<template>
  <div class="tamanho">

   <header class="p-3 bg-dark text-white border-bottom">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
        <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
          <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg>
        </a>

        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <li><a href="#" class="nav-link px-2 text-secondary">Home</a></li>
          <li><a href="#" class="nav-link px-2 text-white navlinkcolor">Features</a></li>
          <li><a href="#" class="nav-link px-2 text-white">Pricing</a></li>
          <li><a href="#" class="nav-link px-2 text-white">About</a></li>
        </ul>

        <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
          <input type="search" class="form-control form-control-dark text-white bg-dark" placeholder="Search..." aria-label="Search">
        </form>

        <div class="text-end">
          <button type="button" class="btn btn-outline-light me-2">Login</button>
          <button type="button" class="btn btn-outline-light">Sign-up</button>
        </div>
      </div>
    </div>
  </header>

<main>
  <div class='center'>
  <div class="cardsbox">
    <Card Imagem = 'https://super.abril.com.br/wp-content/uploads/2020/06/18-06_Dark_SITE.jpg'/>
   <Card Imagem = 'https://s1.static.brasilescola.uol.com.br/be/conteudo/images/imagem-em-lente-convexa.jpg'/>
   <Card Imagem = 'https://static.preparaenem.com/2021/12/imagem-invertida-esfera.jpg'/>
</div>
</div>
</main>


<div class="rodape border-top">
<div class="container ">
  <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 ">
    <div class="col-md-4 d-flex align-items-center">
      <a href="/" class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
        <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"/></svg>
      </a>
      <span class="mb-3 mb-md-0 text-muted">&copy; 2022 Company, Inc</span>
    </div>

    <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
      <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" class="githubicon" 
      alt="">
      <img src="https://iconape.com/wp-content/files/yd/367773/svg/logo-linkedin-logo-icon-png-svg.png" class="githubicon" alt="">
    </ul>
  </footer>
</div>
</div>

</div>
</template>

<style>
</style>
