<template>
  <div>
    <div id="navber">
      <div class="navber-link">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/videos">Videos</NuxtLink>
      </div>
    </div>
    <div id="default-body">
      <Nuxt />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#navber {
  height: 40px;
  width: 100%;
  background-color: #333;
  .navber-link {
    max-width: 800px;
    margin: auto;
    a {
      color: white;
      text-decoration: none;
      margin-right: 1rem;
    }
  }
}
#default-body {
  max-width: 800px;
  margin: auto;
}
</style>
