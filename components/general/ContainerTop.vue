<template>
  <div class="container">
    <div class="item-1" style="background-color: green">Conteúdo do item 1</div>
    <div class="item-2" style="background-color: red">Conteúdo do item 2</div>
  </div>
</template>

<script>
export default {
  name: 'ContainerTop',
};
</script>

<style>
.container {
  display: grid;
  grid-template-columns: 60% 40%;
  height: calc(100vh - 148px);
}
</style>
