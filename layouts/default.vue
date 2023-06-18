<template>
  <div>
    <div id="navber">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/videos">Videos</NuxtLink>
    </div>
    <Nuxt />
  </div>
</template>

<script>
export default {}
</script>

<style>
*,
*:before,
*:after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#navber {
  height: 40px;
  width: 100%;
  background-color: #333;
}
#navber a {
  color: white;
  text-decoration: none;
  margin-right: 1rem;
}
</style>
