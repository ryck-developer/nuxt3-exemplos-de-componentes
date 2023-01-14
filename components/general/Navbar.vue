<template>
  <div>
    <header>
      <a href="#">LOGO</a>
      <p>ss</p>
      <nav>
        <ul>
          <li><a href="#">Página inicial</a></li>
          <li><a href="#">Sobre</a></li>
          <li><a href="#">Contato</a></li>
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
ul, li {
  margin: 0px;
  padding: 0px;
  list-style: none;
}

/* Definir tamanho e fonte para todos os elementos dentro das listas */
ul, li p {
  font-size: 13px;
  font-family: Arial;
}

/* Remover sublinhado nos links */
a {
  text-decoration: none;
}

/* Definir o container header como um elemento flexível e alinhar seus elementos com espaço entre eles */
header {
  display: flex;
  justify-content: space-between;
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
