<template>
  <div class="HookOne">
    <button @click="subtrair">-</button>
    <span>{{ numero }}</span>
    <button @click="adicionar">+</button>
  </div>
</template>

<script>
export default {
  name: 'HookOne',
  data() {
    return {
      numero: 10,
    };
  },
  methods: {
    adicionar() {
      this.numero++;
    },
    subtrair() {
      this.numero--;
    },
  },
};
</script>

<style>
button {
  padding: 10px 20px;
  margin: 10px;
}
.HookOne {
  display: flex;
  border: 0px solid;
  border-radius: 10px;
  background: #f0f0f0;
  justify-content: center;
  align-items: center;
}
</style>
