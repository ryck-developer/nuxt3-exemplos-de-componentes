<template>
  <div>
    <nav>
      <ul>
        <li><a href="#">Página inicial</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: ['message', 'type'],
};
</script>
