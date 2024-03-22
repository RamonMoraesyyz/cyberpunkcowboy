<template>
  <div class="flex flex-col items-center justify-center h-screen bg-black text-white">
    <h1 class="text-5xl font-bold mb-4">Cyberpunk Cowboy Project</h1>
    <br>
    <br>
    <div class="max-w-lg mx-auto">
      <p class="text-md md:text-center mb-8">
        Este projeto harmoniza a tecnologia com a música, combinando imagens e textos criados por IA, 
        além de contar com músicas de autoria e produção própria (oriundas do meu laboratório musical). 
        Nele, convergem três elementos essenciais: a visualidade, a narrativa e a melodia.
      </p>
      <div class="grid grid-cols-2 gap-4">
        <nuxt-link to="/cyberpunkcowboy">
          <div>
            <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full">
              Cyberpunk Cowboy n°1
            </button>
          </div>
        </nuxt-link>
        <nuxt-link to="/uriki">
          <div>
            <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full">
              Uriki Indians n°2
            </button>
          </div>
        </nuxt-link>
        <nuxt-link to="/spider">
          <div>
            <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full">
              Lady Spider n°3
            </button>
          </div>
        </nuxt-link>
        <nuxt-link to="/bongomaster">
          <div>
            <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full">
              Bongo Master n°4
            </button>
          </div>
        </nuxt-link>
        <nuxt-link to="/bossanovasunday">
          <div>
            <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full">
              Bossa Nova Sunday n°5
            </button>
          </div>
        </nuxt-link>
        <nuxt-link to="/monsterfuzz">
          <div>
            <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded w-full">
              Monster Fuzz n°6
            </button>
          </div>
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

<style scoped>
.grid {
  display: grid;
}
.grid-cols-2 {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}
.gap-4 {
  gap: 1rem;
}
</style>