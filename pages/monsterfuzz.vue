<template>
    <div class="relative bg-black text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="../public/monsterfuzz.jpg" class="w-full h-auto md:h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-12 mt-1">Monster Fuzz n°6</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-4">
          <label class="text-lg">Produção: 21/03/2024</label>
          
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg block mb-2">A dupla de stoner metal Monsterfuzz emergiu como uma força singular nos círculos underground de Night City e além. Seus membros, dois animais mutantes, são sobreviventes de experimentos cruéis realizados pelo alto escalão da sociedade.

            Monsterfuzz encontrou sua voz através de músicas que refletem sua jornada de dor e resiliência. Com apresentações carregadas de energia e uma estética visual única, eles rapidamente conquistaram uma base de fãs devota nos bares mais sombrios da cidade.
            
            <br>
            <br>
            Suas colaborações com artistas visuais não apenas enriquecem suas performances, mas também constroem um universo estético que mergulha os espectadores em um mundo de distopia e rebelião. 
            A parceria com Steel Rider, uma figura lendária do cenário musical, trouxe ainda mais destaque à Monsterfuzz, solidificando-os como ícones do stoner metal com uma mensagem poderosa de resistência e autenticidade.


            </label>
        </div>
  
        <!-- Campo para o player de música -->
        <div class="w-full mb-4 md:mt-10">
          <audio controls class="w-full">
            <source src="../public/monsterfuzz.mp3" type="audio/mpeg">
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