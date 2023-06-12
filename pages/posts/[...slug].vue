<template lang="pug">
div.mb-6
  div.post.narrow.card
    div.card-content
      h1.title {{ post.title }}
      p.subtitle {{ post.subtitle }}
      div.content
        ContentDoc
</template>

<script setup>
  const { path } = useRoute()

  const { data: post } = await useAsyncData(`content-${path}`, () => {
    return queryContent().where({ _path: path }).findOne()
  })
</script>
