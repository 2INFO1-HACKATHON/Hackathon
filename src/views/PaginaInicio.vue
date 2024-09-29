<script setup>
function scrollToSection(){

}






</script>
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
      <h1>FixTudo</h1>
      <h2>Sua casa em boas mãos</h2>
      <p>Manutenção e cuidado com carinho</p>
    </div>

    <div class="sobrenos">
<div ref="sectionToScroll">
      <h3>Sobre Nós</h3>
      <p>
        Bem-vindo(a) à Fix Tudo, onde transformamos suas necessidades em
        <hr>soluções práticas e
        personalizadas!
        Somos uma empresa dedicada a
        <hr> conectar você com profissionais qualificados
        nas áreas de manutenção,
        <hr> limpeza, cuidados pessoais e culinária.
      </p>
      <p>Nosso compromisso é com a excelência e a satisfação dos nossos
        <hr> clientes.
      </p>

</div>
    </div>
    <div class="intera">


      <div class="left-side">
        <h4>Fácil e Rápido</h4>
        <h2>Como Funciona?</h2>
        <p>Basta apenas um toque e deixa que o resto a gente facilita para você.</p>
        <p class="small-text">Não leva nem 10 segundos.</p>
        <button class="cta-button">
          <i class="whatsapp-icon"></i> Solicitar Orçamento
        </button>
      </div>
      <div class="right-side">
        <div class="card">
          <p class="card-number">01.</p>
          <p>Toque em qualquer botão do site para ser atendido por nossa equipe por Whatsapp.</p>
        </div>
        <div class="card">
          <p class="card-number">02.</p>
          <p>Escolha qual o tipo de serviço desejado e tenha rapidamente seu orçamento.</p>
        </div>
        <div class="card">
          <p class="card-number">03.</p>
          <p>Receba nossos termos e agende o melhor horário para a limpeza.</p>
        </div>
        <div class="card blue-card">
          <p class="card-number">04.</p>
          <p>Receba em tempo recorde nossos funcionários no seu estabelecimento ou casa.</p>
        </div>
      </div>
    </div>
  </div>
</template>







<style scoped>
.container {
  display: flex;
  flex-direction: column;
  background-color: #e2e2e2;
  width: 100%;
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



.hero {
  margin-left: 40px;
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

.sobrenos {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 200px;

}

.sobrenos img {
  width: 300px;
  height: 300px;
  border-radius: 0.5rem;
  margin-bottom: 1.5rem;
}

.sobrenos p {
  color: #666;
  font-size: 1rem;

}

.sobrenos h3 {
  padding: 10px;


}

.intera {
  display: flex;
  height: 800px;
  align-items: center;
  justify-content: center;
  gap: 8vw;
  background-color: white;
}




.left-side {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-left: 10px
}
.left-side h2{
  color: #00626d;
}

.right-side {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  height: 10vh;
  padding: 10px;




}

.card {
  border: 1px solid #ccc;
  padding: 20px;
  border-radius: 10px;
  width: 15vw;

}

.blue-card {
  background-color: #2AB0BF;
}

.card-number {
  font-size: 24px;
  font-weight: bold;
  color: teal;
  margin-bottom: 10px;
}

.cta-button {
  background-color: rgb(150, 151, 150);
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  width: 10vw;

}

.whatsapp-icon {}

.small-text {
  font-size: 12px;
  color: #888;
}
</style>
