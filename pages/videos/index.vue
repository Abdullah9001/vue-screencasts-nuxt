<template>
  <div>
    <div v-for="video in videos" :key="video.id">
      <nuxt-link :to="'/videos/' + video.id">{{ video.name }}</nuxt-link>
    </div>
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
}
</script>

<style lang="scss" scoped></style>
