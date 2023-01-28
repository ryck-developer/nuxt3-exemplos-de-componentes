<template>
  <div class="container">
    <div class="item-1">
      <div class="title">
        <div class="title-box">
          <p>luiz</p>
          <p class="enfase">focado em transição de</p>
          <p>carreira</p>
        </div>
      </div>
      <div class="description">
        <p>
          Temos desafios, lives, eventos, tiramos dúvidas e achamos uma
          colocação para você. Quer fazer parte? Clique no botão<p style='margin-top: -18px !important;'> abaixo:</p>
        </p>
      </div>
      <div class="button-participar">
        <button>Participar</button>
      </div>
    </div>
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

.title > .title-box > p {
  font-size: 52px;
  line-height: 0.3;
  font-weight: 700;
  color: #2f2f2f;
}

.title-box {
  margin-top: 80px;
  margin-left: 144px !important;
}

.title > .title-box > .enfase {
  color: #717cff;
}

.description > p {
  color: #7d7d7d;
  margin-left: 144px !important;
  font-size: 19px;
  line-height: 1.7;
}
.button-participar > button {
  background: #4654fd;
  border: 0px solid;
  border-radius: 8px;
  padding: 10px 60px;
  font-size: 24px;
  margin-left: 144px !important;
  color: white;
}

<!-- CSS media query dentro de um stylesheet -->
@media (max-width: 498px)
{
  .title>.title-box>p {
    font-size: 42px;
    font-weight: 700;
    line-height: 1;
  }
}
</style>
