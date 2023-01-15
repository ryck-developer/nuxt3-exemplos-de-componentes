<template>
  <div>
    <header>
      <a href="#"
        ><img
          src="https://raw.githubusercontent.com/ryck-developer/luiz-henrique-chaves/main/logo.png"
          alt=""
      /></a>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Compromissos</a></li>
          <li><a href="#">Notícias</a></li>
          <li><a href="#">Agenda</a></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<style>
/* Remover margem e padding das listas e definir que não terá marcadores */
ul,
li,
a,
body {
  margin: 0px;
  padding: 0px;
  list-style: none;
}

/* Definir tamanho e fonte para todos os elementos dentro das listas */
ul,
li,
p,
a {
  font-size: 16px;
  font-family: arial, sans-serif;
  font-weight: 600;
}

/* Remover sublinhado nos links */
a {
  text-decoration: none;
  padding: 9px;
  color: #4d4d4d;
}

/* Definir margem da logo para a mesma margem do menu*/
header > a {
  margin-left: 10px;
}

/* Definir o container header como um elemento flexível e alinhar seus elementos com espaço entre eles */
header {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

header > a > img {
  margin-left: 100px;
  margin-top: 48px;
}

/* Definir o elemento <ul>(menu) como um elemento flexível */
nav > ul {
  display: flex;
}

/* Adicionar padding de 10px para cada elemento li dentro do <ul>(menu) */
nav > ul > li {
  padding: 10px;
}
</style>
