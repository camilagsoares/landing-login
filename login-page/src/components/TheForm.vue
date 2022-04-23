<template>
  <div>
    <p>{{ text }}</p>
    <h3>{{ textLogin }}</h3>

    <label>E-mail</label>
    <input/>
    <label>Senha</label>
    <input type="password"/>
    <button>Entrar</button>
    <button>Ou faça login com o Google</button>
  </div>
</template>

<script>
export default {
  name: "TheForm",

  data() {
    return {
      text: "Bem vindo de volta",
      textLogin: "Faça login na sua conta"
    };
  },
  // props: {
  //   msg: String
  // }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
input{
  width: 350px;
  height: 50px;
  border-radius: 4px;
  border: 1px solid #E8E8E8;
  margin: 3px;
}

button{
  background: #04C35C;
  color: white;
  cursor: pointer;
}
</style>
