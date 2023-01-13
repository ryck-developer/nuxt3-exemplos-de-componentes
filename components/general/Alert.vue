<template>
  <div class="alert" :class="type">
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'Alert',
  props: ['message', 'type'],
};
</script>
