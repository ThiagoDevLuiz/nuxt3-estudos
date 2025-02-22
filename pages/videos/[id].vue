<template>
  <div>Você está na página do vídeo {{ $route.params.id }}</div>
  <VideoDetalhes />
  <VideoControlePlay />
</template>

<script setup>
definePageMeta({
  layout: "exibicao",
});
</script>
