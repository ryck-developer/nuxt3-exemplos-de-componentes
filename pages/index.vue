<template>
  <div>
    <title>Desafio Front-end 2 - Pessoas de Tech</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

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
