<script>
 import Frontpage from '../components/my_componets/Frontpage.vue'
 import Nav from '../components/my_componets/Nav.vue'
 import Footer from '../components/my_componets/Footer.vue'
 import Card from '../components/my_componets/Card.vue'

 export default {
  data() {
    return {
      superHeroeList: [],
    }
  },
  components: {
    Frontpage,
    Nav,
    Card,
    Footer
},
  created() {
    fetch('https://akabab.github.io/superhero-api/api/all.json')
    
   
      .then((response) => response.json())
      .then((data) => {this.superHeroeList = data})
      .catch(function (error) {
        console.log('Hubo un problema con la petición Fetch:' + error.message)
      })
  },
}
</script>

<template>
    <Frontpage/>
     <Nav/>
  <main>
   <div class="d-flex flex-wrap ms-5 me-5 justify-content-center">
      <div class="d-flex flex-wrap ms-5 me-5">
        <div v-for="heroe in superHeroeList.slice(0, 12)" :key="key">
          <Card :heroe="heroe" />
        </div>
      </div>
    </div>
  </main>
  <Footer/>
</template>


<style></style>