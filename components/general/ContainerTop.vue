<template>
  <div class="container">
    <div class="item-1" style="background-color: green">Conteúdo do item 1</div>
    <div class="item-2" style="background-color: red; color: white">
      Conteúdo do item 1
      <div class="img"></div>
    </div>
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
.img {
  width: 100px;
  height: 100px;
  background: yellow;
  align-self: flex-end;
}

.item-2 {
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
}
</style>
