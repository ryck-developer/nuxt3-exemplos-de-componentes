<template>
  <div>
    <a :href="url"><img :src="logo" alt=""></img></a>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: ['message', 'type'],
  data() {
    return {
      texto: 'ola mundo',
    };
  },
};
</script>
