<template>
  <div>
    <title>Desafio Front-end 2 - Pessoas de Tech</title>
    <Navbar />
    <ContainerTop />
  </div>
</template>

<script>
import Navbar from '~/components/general/Navbar.vue';
import ContainerTop from '~/components/general/ContainerTop.vue';

export default {
  components: {
    Navbar,
    ContainerTop,
  },
};
</script>
