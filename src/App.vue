<script>
import Apptitle from "./components/Apptitle.vue"
import Hero from "./components/Hero.vue"
export default {

  data(){
    return{

    }
  },
  components: {
    Apptitle,
    Hero,
  },
  methods: {

  },

}

</script>

<template>

  <main>

    <div class="my-container">

      <Apptitle/>
  
      <Hero/>

    </div>

  </main>

</template>

<style scoped>

 h1{
  margin: 0 auto;
  text-align: center;
}

</style>
