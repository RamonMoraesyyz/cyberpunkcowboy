<template>
    <div class="relative bg-black text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="../public/indiansuriki.jpeg" class="w-full h-auto md:h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-10 mt-1">Uriki Indians n°2</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-4">
          <label class="text-lg">Produção: 20/01/2024</label>
          
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg block mb-2">No coração da densa floresta tropical, o povo indígena Uriki praticava um ritual sagrado à luz da lua, onde, ao som de tambores e flautas, evocavam os espíritos de seus antepassados.
             Vestidos com ornamentos de penas, dançavam em círculo, entoando cânticos ancestrais para estabelecer uma ligação transcendental com a natureza e seus antigos guias espirituais. 
             Liderados por um ancião, o ritual atingia seu ápice, dissipando as fronteiras entre o mundo terreno e espiritual. Os Uriki acreditavam que, nesses momentos, a sabedoria ancestral era compartilhada pelos espíritos, proporcionando orientação e bênçãos para a tribo. 
             Ao nascer do sol, agradeciam aos espíritos, mantendo viva a chama da espiritualidade e harmonia com a natureza para as gerações futuras. </label>
        </div>
  
        <!-- Campo para o player de música -->
        <div class="w-full mb-4 md:mt-10">
          <audio controls class="w-full">
            <source src="../public/uriki.aac" type="audio/mpeg">
          </audio>
        </div>
        
      </div>
    </div>
  </template>