<template>
  <div>
    <h1>Cadastro</h1>
    <form>
      <label>Nome:</label>
      <input type="text" />
      <label>Email:</label>
      <input type="email" />
      <label>Senha:</label>
      <input type="password" />
      <button type="submit">Cadastrar</button>
    </form>
    <router-link to="/login">Já tem uma conta? Faça login</router-link>
  </div>
</template>

<script>
export default {
  name: "Register",
};
</script>
