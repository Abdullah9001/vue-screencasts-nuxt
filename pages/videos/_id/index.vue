<template>
  <div>
    <h2>We are in vedio {{ video.name }}</h2>
    <NuxtLink :to="'/videos/' + video.id + '/edit'"
      ><button>Edit</button></NuxtLink
    >
  </div>
</template>

<script>
export default {
  props: ['video'],
}
</script>

<style lang="scss" scoped></style>
