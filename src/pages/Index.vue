<template>
  <q-page class="flex flex-center column q-gutter-md">
    <img src="/AppIcon.png" />
    <div class="text-h6 text-center">
      Greetings! The site has been moved to a new domain. Click
      <a href="https://and249.codes/">here</a> if it doesn't redirect.
    </div>
  </q-page>
</template>

<style lang="scss" scoped>
img {
  max-width: 200px;
}

a {
  color: white;
  text-decoration: underline;

  &:hover {
    text-decoration: none;
  }
}
</style>

<script setup>
window.location.replace("https://and249.codes/");
</script>
