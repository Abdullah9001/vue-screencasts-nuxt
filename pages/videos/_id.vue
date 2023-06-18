<template>
  <div>
    <NuxtChild :video="video" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      videos: [
        { id: '16', name: 'Intro to nuxt.js' },
        {
          id: '1',
          name: 'Intro to Vue.js',
        },
        {
          id: '71',
          name: 'Use Advence Tecnology',
        },
      ],
    }
  },
  computed: {
    video() {
      return this.videos.find((v) => v.id === this.$route.params.id)
    },
  },
}
</script>

<style lang="scss" scoped></style>
