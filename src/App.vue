<script setup>
  import Counter from './components/Counter.vue'
  import FrontHeading from './components/FrontHeading.vue'
</script>

<template>
  <main class="container-max">
    <section class="row-block f-center pt-60">
      <img alt="Vue logo" src="./assets/img/logo.png" />
    </section>
    <section class="row-block">
      <FrontHeading class="pt-60" msg="Hello Vue 3 + Vite + hgrid-css" />
    </section>
    <section class="row pt-40">
      <div class="column">
        <Counter />
      </div>
      <div class="column phone-landscape-mt-40">
        <h2 class="h4">What is hgrid-css?</h2>
        <p>
          <code>hgrid</code> is a lightweight, laptop-first CSS utility kit with a mostly flat learning curve. It's 
          a starting point intended to make HTML work out of the box. Built with Sass, it integrates smoothly into any Node.js 
          driven project.
        </p>
        <p>
          <small>
            It's not a UI framework, but provides defaults so you can start building without having to deal with 
            browser quirks, unstyled elements and basic responsiveness.
          </small>
        </p>
        <p>
          <a href="https://hgrid.io">Hgrid documentation</a>
        </p>
      </div>
    </section>
  </main>

</template>

<style>
</style>
