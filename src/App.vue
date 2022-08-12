<template>
  <div id="app" class="principal">
    <span>App - Instancia do Vue</span>
    <Entrada />
  </div>
</template>

<script>
//Codigo JavaScript simples
import Entrada from "./views/Entrada.vue";

//Componente Vue.
export default {
  name: "App",
  components: { Entrada },
  data() {
    return {
      titulo: "Meu primeiro aplicativo publicado",
    };
  },
};
</script>
<style>
html {
  font-size: 62.5%;
}

.principal {
  background-color: #a21010;
  padding: 1rem;
  color: white;
  border-radius: 0.5rem;
  padding: 1rem;
  font-size: 3rem;
  width: 40rem;
  text-align: center;
}
</style>
