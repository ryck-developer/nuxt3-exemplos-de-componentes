<template>
  <div>
    <h1>hello</h1>
    <Alert
      :message="messages.success_signup.text"
      v-bind:type="messages.success_signup.class"
    ></Alert>
  </div>
</template>

<script>
import Alert from '~/components/general/Alert.vue';
export default {
  components: {
    Alert,
  },
  data() {
    return {
      messages: {
        success_signup: {
          text: 'Bem-Vindo ao site, agora que você é um colaborador, que tal dar uma olhada na sessão de aprendizado?',
          class: 'information',
        },
      },
    };
  },
};
</script>
