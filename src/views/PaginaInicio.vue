<template>
  <div class="container">
    <header>
      <RouterLink to="/"><img src="../assets/imagens/logo.png" alt="logo" /> </RouterLink>
      <button @click="scrollToSection" class="scroll-button">Sobre Nós</button>
      <button>Serviços</button>
      <RouterLink to="/PaginaLogin">Entrar</RouterLink>
      <RouterLink to="/PaginaSignup">Criar Conta</RouterLink>
    </header>

    <div class="hero">
      <h2>Sua casa em boas mãos</h2>
      <p>Manutenção e cuidado com carinho</p>
    </div>

    <div class="illustration">
      <p>
        Bem-vindo(a) à Fix Tudo, onde transformamos suas necessidades em soluções práticas e
        personalizadas! Somos uma empresa dedicada a conectar você com profissionais qualificados
        nas áreas de manutenção, limpeza, cuidados pessoais e culinária.
      </p>
      <p>Nosso compromisso é com a excelência e a satisfação dos nossos clientes.</p>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1.5rem;
  background-color: #f7f7f7;
  width: 100vw;
}
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

h1 {
  font-size: 2.5rem;
  font-weight: bold;
  color: #333;
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
nav a:last-child {
  margin-right: 0;
}

.hero {
  text-align: center;
  margin-bottom: 1.5rem;
}

.hero h2 {
  font-size: 1.5rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
}

.hero p {
  color: #666;
}

.illustration {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.illustration img {
  width: 300px;
  height: 300px;
  border-radius: 0.5rem;
  margin-bottom: 1.5rem;
}

.illustration p {
  color: #666;
  font-size: 1.25rem;
  margin-bottom: 1.5rem;
}
</style>
