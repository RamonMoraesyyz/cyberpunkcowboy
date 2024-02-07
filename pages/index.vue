<template>
  <div class="flex flex-col items-center justify-center h-screen bg-black text-white">
    <h1 class="text-3xl font-bold mb-4 md:mb-8 text-center">Cyberpunk Cowboy Project</h1>
    <p class="text-sm md:text-base mb-4 md:mb-8 text-center">
      Este projeto une a tecnologia e música, com imagens e textos gerados por IA, <br>
      e com músicas de autoria e produção própria (meu laboratório musical) <br>
      se juntam três elementos e sensações: a imagem, a história por trás e a música.
    </p>
    <div class="flex flex-col md:flex-row justify-center w-full md:w-1/2">
      <div class="space-y-4 md:mr-4">
        <nuxt-link to="/ciberpunkcowboy">
          <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full md:w-auto">
            Cyberpunk Cowboy n°1
          </button>
        </nuxt-link>
        <nuxt-link to="/uriki">
          <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full md:w-auto">
            Uriki Indians n°2
          </button>
        </nuxt-link>
      </div>
      <div class="space-y-4 mt-4 md:mt-0">
        <nuxt-link to="/spider">
          <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full md:w-auto">
            Lady Spider n°3
          </button>
        </nuxt-link>
        <nuxt-link to="/bongomaster">
          <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full md:w-auto">
            Bongo Master n°4
          </button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuInicial'
}
</script>