<script setup>
  import { ref } from 'vue'
  const count = ref(0)
</script>

<template>
  <p>
    Recommended IDE setup:
    <a href="https://code.visualstudio.com/" target="_blank">VSCode</a>
    +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
  </p>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Documentation
    </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button type="button" class="radius push14v" @click="count++">The count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<style lang="scss">
  @use 'hgrid-css/sass/variables/_variables' as *;

  .variable-test {
    background-color: $color-red; // internal hgrid variable exposed with @use
  }

  .custom-property-test {
    background-color: var(--color-red); // hgrid custom property, no @use/import required
  }
</style>
