<template>
  <main
    id="main"
    class="w-full max-w-screen-lg mx-auto px-4 sm:px-6 md:px-8 pt-16"
  >
    <Intro class="mb-24 md:mb-32" />

    <ExistingPaper class="mb-24 md:mb-32" />

    <LineChart class="mb-24 md:mb-32" />

    <OurAnalysis class="mb-24 md:mb-32" />

    <Summary class="mb-24 md:mb-32" />

    <Hygiene class="mb-24 md:mb-32" />

    <Sources class="mb-24 md:mb-32" />
  </main>
</template>

<script>
import { getPageHead } from "~/utils"

export default {
  head() {
    return getPageHead({
      instance: this,
      title: null,
    })
  },
}
</script>
