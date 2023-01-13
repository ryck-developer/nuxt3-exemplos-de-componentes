<template>
  <div>
    <h1>hello</h1>
    <Alert v-bind:message="'Hello World'" v-bind:type="'teste'"></Alert>
  </div>
</template>

<script>
import Alert from '~/components/general/Alert.vue';
export default {
  components: {
    Alert,
  },
};
</script>
