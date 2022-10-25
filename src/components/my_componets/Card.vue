<script>
import { mapActions, mapState } from 'pinia'

export default {
  props: {
    heroe: Object,
  }
 
}
</script>

<template>
  <div class="d-flex cards_container">
    <div class="card mt-5 me-5 ms-5">
      <!-- <img src="src/assets/foto.jpg" class="card-img-top pb-4 pe-3 ps-3 pt-3" alt="fotografía"> -->
      <img :src="heroe.images.md" class="card-img-top pb-4 pe-3 ps-3 pt-3" :alt="heroe.name" />
      <div class="card-body d-flex">
        <h5 class="card-title">{{ heroe.name }}</h5>
        <a href="/details" class="btn ms-5 pb-3">Más</a>
      </div>
    </div>
  </div>
 
</template>

<style>
  .cards_container{
    margin-left: 10%;
  }

  .card{
    width: 19rem;
    border: 2px solid black;
  }

  .btn{
    width: 60px;
    height: 35px;
    color: white;
    background-color: #88ad99;
  }

  .btn:hover{
    background-color: black;
    color: white;
  }

  h5{
    font-family: 'Klee One', cursive;
  }

</style>
