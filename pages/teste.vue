<template>
  <div>
    <Navbar />
  </div>
</template>

<script>
import Navbar from '~/components/general/Navbar.vue';

export default {
  components: {
    Navbar,
  },
  data() {
    return {
      header: {
        logo: {
          link: 'Bem-Vindo ao site, agora que você é um colaborador, que tal dar uma olhada na sessão de aprendizado?',
          imagem: 'information',
        },
      },
    };
  },
};
</script>
