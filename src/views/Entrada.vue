<template>
  <div class="entrada">
    <span>Entrada</span>
    <cliente />
    <div class="seccion"><span>seccion</span></div>
  </div>
</template>

<script>
import Cliente from "../components/Cliente.vue";
export default {
  components: { Cliente },
};
</script>

<style>
.entrada {
  background-color: #553f75;
  padding: 1rem;
  margin: 1rem;
  font-size: 2.6rem;
}
.seccion {
  background-color: rgb(163, 168, 0);
  padding: 1rem;
  margin: 1rem;
  font-size: 2.4rem;
}
</style>
