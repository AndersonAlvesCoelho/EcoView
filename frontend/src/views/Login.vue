<template>
  <div>
    <h1>Login</h1>
    <form>
      <label>Email:</label>
      <input type="email" />
      <label>Senha:</label>
      <input type="password" />
      <button type="submit">Entrar</button>
    </form>
    <router-link to="/register">Ainda não tem uma conta? Cadastre-se</router-link>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>
