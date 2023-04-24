<script setup>
  const cidades = [
    'São Paulo',
    'Rio de Janeiro',
    'Belo Horizonte',
    'Salvador',
    'Fortaleza',
    'Curitiba',
    'Manaus',
    'Recife',
    'Porto Alegre',
    'Brasília'
]
</script>

<template>
  <h1>lista de cidades</h1>
  <ul>
    <li v-for="(cidade, index) in cidades" :key="index">{{ cidade }}</li>
  </ul>
</template>

<style scoped>
</style>
