<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<script>
export default {
  name: 'App',
  data() {
    return {}
  }
}
</script>

<style></style>
