<template>
  <div class="seccion">{{ `${name} ${surname} , idade: ${41}` }}</div>
</template>

<script>
export default {
  data() {
    return {
      name: "Isaac",
      surname: "Newton",
      idade: 41,
    };
  },
};
</script>

<style scoped>
.seccion {
  background-color: rgb(155, 155, 155);
  padding: 1rem;
  margin: 1rem;
  font-size: 2.4rem;
}
</style>
