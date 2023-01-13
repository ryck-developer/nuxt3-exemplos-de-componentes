<template>
  <div>
    <h1>hello</h1>
    <Alert
      :message="messages.success_signup.text"
      v-bind:type="messages.success_signup.class"
    ></Alert>

    <Alert
      :message="'Parabéns agora você está registrado da guilda'"
      v-bind:type="messages.success_signup.class"
    ></Alert>
  </div>
</template>

<script>
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
