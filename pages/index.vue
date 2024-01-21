<template>
  <div class="relative bg-black text-white flex h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-1/2">
      <img src="/cyberpunkcowboy.png" class="w-full h-full object-cover transform scale-70" />
    </div>

    <!-- Conteúdo direito (título, data, detalhes) -->
    <div class="w-1/2 p-8 flex flex-col justify-center">

      <!-- Título -->
      <h1 class="text-4xl font-bold mb-10 mt-1">Cyberpunk cowboy n°1</h1>

      <!-- Campo para a data da produção -->
      <div class="mb-4">
        <label class="text-lg">Produção: 11/01/2024</label>
        <input type="text" class="bg-black border-b-2 border-white text-white p-2 w-full">
      </div>

      <!-- Campo para detalhes -->
      <div class="mb-4">
        <label class="text-lg"> Em um futuro distante, Steel Rider, o cowboy cyberpunk, percorre as ruas de uma cidade futurística em seu cavalo de metal, 
          tocando blues noturno nos bares decadentes. 
          Com seu chapéu sombreado e olhos cibernéticos cintilantes, 
          ele é mais do que um músico; é um guardião das histórias esquecidas da humanidade. 
          Em um mundo onde a tecnologia e a solidão dominam, Steel Rider personifica a resistência, mantendo viva a tradição do blues e encontrando a humanidade nas notas de sua guitarra elétrica e nos relinchos metálicos de seu leal companheiro. </label>
        
      </div>

      <!-- Campo para o player de música -->
      <div>
        
        <audio controls class="w-full mt-10">
          <source src="../public/cyberpunkcowboyn1110124.mp3" type="audio/mpeg">
        </audio>
      </div>
      
    </div>
  </div>
</template>