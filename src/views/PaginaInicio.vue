<script setup></script>
<template>
  <div class="container">
    <div class="header">
      <RouterLink to="/"> <img src="../assets/imagens/logo.png" alt="" /></RouterLink>
      <button @click="scrollToSection" class="scroll-button">Sobre Nós</button>
      <button>Serviços</button>
      <RouterLink to="PaginaLogin">Entrar</RouterLink>
      <RouterLink to="PaginaSignup">Criar Conta</RouterLink>
    </div>
    <div class="content">
      
    </div>
  </div>
</template>

<style scoped>
.header {
  background-color: rgb(0, 0, 0);
  height: 3vh;
  display: flex;
  justify-content: start;
}
img {
  width: 160px;
  height: 130px;
  display: flex;
  flex-direction: column;
}
</style>
