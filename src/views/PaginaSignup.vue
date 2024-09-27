<script setup></script>


<template>
    <div class="login-container">
      <div class="login-panel">
        <h1 class="welcome-title">Bem-vindo!</h1>
        <p class="description">Para manter-se conectado entre com seus dados pessoais</p>
        <button class="login-button">Entrar</button>
      </div>
      <div class="register-panel">
        <h2 class="register-title">Criar Conta</h2>
        <p class="description">Use seu email para se registrar</p>
        <form class="register-form">
          <div class="form-group">
            <input type="text" placeholder="Nome" class="form-input" required />
          </div>
          <div class="form-group">
            <input type="email" placeholder="Email" class="form-input" required />
          </div>
          <div class="form-group">
            <input type="password" placeholder="Senha" class="form-input" required />
          </div>
          <button type="submit" class="register-button">Cadastrar-se</button>
        </form>
      </div>
    </div>
  </template>
  
  <style scoped>
  .login-container {
    display: flex;
    height: 100vh;
  }
  
  .login-panel {
    width: 50%;
    background-color: #0097a7; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 2rem;
    color: #ffffff; 
  }
  
  .welcome-title {
    font-size: 2rem;
    font-weight: bold;
  }
  
  .description {
    margin-top: 1rem;
    font-size: 1.25rem;
  }
  
  .login-button {
    margin-top: 1.5rem;
    background-color: #ffffff; 
    color: #0097a7;
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    cursor: pointer;
  }
  
  .login-button:hover {
    background-color: #00b5b5;
  }
  
  .register-panel {
    width: 50%;
    background-color: #ffffff; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 2rem;
  }
  
  .register-title {
    font-size: 1.75rem;
    font-weight: bold;
    color: #0097a7; 
  }
  
  .register-form {
    width: 100%;
    max-width: 24rem;
    margin-top: 1.5rem;
  }
  
  .form-group {
    margin-bottom: 1rem;
  }
  
  .form-input {
    border: 1px solid #a0a0a0; 
    border-radius: 0.5rem;
    padding: 0.5rem;
    width: 100%;
  }
  
  .register-button {
    background-color: #0097a7; 
    color: #ffffff; 
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    cursor: pointer;
  }
  
  .register-button:hover {
    background-color: #00b5b5; 
  }
  </style>