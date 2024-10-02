<template>

<header>
      <RouterLink to="/"><img src="../imagens/logo.png" alt="logo" /> </RouterLink>
      <button >Sobre Nós</button>
      <button>Serviços</button>
      <RouterLink to="/PaginaLogin">Entrar</RouterLink>
      <RouterLink to="/PaginaSignup">Criar Conta</RouterLink>
    </header>
</template>

<style scoped>
img {
  width: 9vw;
  height: 15vh;
}

header {
  width: 100%;
  display: flex;

  align-items: center;
  margin-bottom: 1.5rem;
}

a {
  margin-right: 1.5rem;
  color: #666;
  text-decoration: none;
}

button {
  margin-right: 1.5rem;
  color: #666;
  text-decoration: none;
  border: none;
  background-color: #ffe0e000;
}
</style>
