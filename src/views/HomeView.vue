<script setup></script>

<template>
  <h1>Home</h1>
  <button @click="$router.push({name:'about'})">Ir para Sobre</button>
  <button @click="$router.push({name:'contact'})">Ir para Contato</button>
  <button @click="$router.push({name:'news'})">Ir para Notícias</button>
  <button @click="$router.push({name:'team'})">Ir para Equipe</button>
</template>
