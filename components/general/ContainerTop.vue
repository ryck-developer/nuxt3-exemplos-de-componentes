<template>
  <div class="container">
    <div class="item-1" style="background-color: green">Conteúdo do item 1</div>
    <div class="item-2">
      <div class="img">
        <img
          src="https://raw.githubusercontent.com/ryck-developer/luiz-henrique-chaves/main/hero.png"
          alt=""
        />
      </div>
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
  width: 490px;
  height: 350px;
  align-self: flex-end;
  background-image: url('https://raw.githubusercontent.com/ryck-developer/luiz-henrique-chaves/main/hero-bg.png');
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
}

.item-2 {
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
}

.img > img {
  width: 500px;
}
</style>
