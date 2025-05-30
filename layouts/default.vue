<template>
    <div>
        <Header></Header>
        <main>
            <slot />
        </main>
        <Footer></Footer>
    </div>
</template>

<script setup lang="ts">
// Typically, you don't need explicit imports for components in Nuxt 3,
// if they are in the `components/` folder (auto-imported by default).
// If you do need to import them manually:

import Header from '~/components/header.vue'
import Footer from '~/components/footer.vue'
</script>
  
