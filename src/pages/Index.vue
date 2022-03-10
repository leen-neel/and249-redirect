<template>
  <q-page class="flex flex-center column q-gutter-md">
    <img src="/AppIcon.png" />
    <div class="text-h6">
      Greetings! The site has been moved to a new domain. Click
      <a href="https://and249.codes/">here</a> if it doesn't redirect.
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageIndex",
});
</script>

<style lang="scss" scoped>
img {
  max-width: 100px;
}

a {
  color: white;
  text-decoration: underline;

  &:hover {
    text-decoration: none;
  }
}
</style>
