<script setup>
  import Navbar from './components/Navbar.vue';
  import Background from './components/Background.vue';

  import Home from './pages/Home.vue';
  import Expertise from './pages/Expertise.vue';
  import MyWork from './pages/MyWork.vue';
  import Work from './pages/Work.vue';
  import Contact from './pages/Contact.vue';
  
</script>

<template class="overflow-hidden w-screen">
  <Background />
  <Navbar />
  <Home />
  <Expertise />
  <MyWork />
  <Work />
  <Contact />

</template>
