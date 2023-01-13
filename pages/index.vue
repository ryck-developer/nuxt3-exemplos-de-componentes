<template>
  <div>
    <h1>hello</h1>
    <Alert
      :message="messages.success.text"
      v-bind:type="messages.success.class"
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
        success: { text: 'Ola Mundo', class: 'success' },
      },
    };
  },
};
</script>
