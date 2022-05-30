<script>
import '../assets/bootstrap.min.css'
import '../assets/animate.min.css'

export default {
    props: ['Imagem']
}
</script>


<template>
  <div class="card border border-secondary bg-transparent rounded animate__animated animate__fadeIn" style="width: 18rem;">
    <img :src="Imagem" class="card-img-top" alt="...">
    <div class="card-body">
      <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque illum impedit unde, aspernatur, minus omnis voluptatum.</p>
    </div>
  </div>

</template>

<style scoped>
.card{margin-left:20px;}
</style>
