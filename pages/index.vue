<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="text-5xl font-bold py-10 bg-gradient-to-r text-transparent bg-clip-text from-green-600 via-green-800 to-green-700">
        Nuxt Tailwindcss
      </h1>
      <div class="links">
        <a
          href="https://github.com/tommypratama/start-nuxt-tailwind/generate"
          target="_blank"
          rel="noopener noreferrer"
          class="inline-block bg-coolgray-900 text-white px-6 py-2 border border-transparent rounded hover:bg-coolgray-800 shadow-md transition-colors duration-150 ease-in"
          type="button"
        >
          Generate New Repo
        </a>
        <a
          href="https://github.com/tommypratama/start-nuxt-tailwind"
          target="_blank"
          rel="noopener noreferrer"
          class="ml-3 inline-block text-coolgray-900 border border-coolgray-900 px-6 py-2 rounded hover:bg-coolgray-800 hover:text-white transition-colors duration-150 ease-in"
          type="button"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
</style>
