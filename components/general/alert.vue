<template>
  <div class="alert" :class="type">
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'alert',
  props: ['message', 'type'],
};
</script>
