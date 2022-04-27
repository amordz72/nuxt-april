<template>
  <main>
    <h1>Home page</h1>
    <NuxtLink to="/about"> About </NuxtLink> <span>|</span>
    <NuxtLink to="/">Home page</NuxtLink>
  </main>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
<style>
main span {
  color: crimson;
}
</style>
