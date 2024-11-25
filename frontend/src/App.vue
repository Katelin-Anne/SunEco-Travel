<template>

    <NavBar />
    <main class="container-fluid">
      <div class="row">
        <router-view /> 
      </div>
    </main>
    <Footer/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue';
import NewComponent from './NewComponent.vue'

export default {
  components: {
    NavBar,
    Footer,
    NewComponent
} 
}

</script>

<style src="./assets/css/style.css">

</style>