<script setup lang="ts">
import { docsLink } from '#macros' assert { type: 'macro' }
</script>

<template>
  <div w-screen h-screen flex="~ col gap2" justify-center items-center>
    <img :src="`${docsLink}/logo.svg`" alt="Vue Macros" h-40 />
    <h1 text-2xl font-mono>Vue Macros is working!</h1>
    <a :href="docsLink" target="_blank">
      📜
      <span text-blue underline underline-offset-3>Documentation</span>
    </a>

    <span opacity-50 text-sm>More features are coming soon!</span>
  </div>
</template>

<style>
html.dark {
  background: #000;
  color: #eee;
}
</style>
