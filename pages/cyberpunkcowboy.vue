<template>
    <div class="relative bg-black text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="/cyberpunkcowboy.png" class="w-full h-auto md:h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-10 mt-1">Cyberpunk cowboy n°1</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-10">
          <label class="text-lg">Produção: 11/01/2024</label>
          
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg block mb-2">Em um futuro distante, Steel Rider, o cowboy cyberpunk, percorre as ruas de uma cidade futurística em seu cavalo de metal, tocando blues noturno nos bares decadentes. 
            Com seu chapéu sombreado e olhos cibernéticos cintilantes, ele é mais do que um músico; é um guardião das histórias esquecidas da humanidade. 
            Em um mundo onde a tecnologia e a solidão dominam, Steel Rider personifica a resistência, mantendo viva a tradição do blues e encontrando a humanidade nas notas de sua guitarra elétrica e nos relinchos metálicos de seu leal companheiro.</label>
        </div>
  
        <!-- Campo para o player de música -->
        <div class="w-full mb-4 md:mt-10">
          <audio controls class="w-full">
            <source src="../public/cyberpunkcowboyn1110124.mp3" type="audio/mpeg">
          </audio>
        </div>

        <div class="mt-4 text-center">
        <nuxt-link to="/">
          <button class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded">
            Back to menu
          </button>
        </nuxt-link>
      </div>
        
      </div>
    </div>
  </template>