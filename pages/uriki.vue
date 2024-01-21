<template>
    <div class="relative bg-black text-white flex h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-1/2">
        <img src="../public/indiansuriki.jpeg" class="w-full h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-1/2 p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-4xl font-bold mb-10 mt-1">Indians Uriki n°2</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-4">
          <label class="text-lg">Produção: 20/01/2024</label>
          <input type="text" class="bg-black border-b-2 border-white text-white p-2 w-full">
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg"> No coração da densa floresta tropical, o povo indígena Uriki praticava um ritual sagrado à luz da lua, onde, ao som de tambores e flautas, evocavam os espíritos de seus antepassados.
             Vestidos com ornamentos de penas, dançavam em círculo, entoando cânticos ancestrais para estabelecer uma ligação transcendental com a natureza e seus antigos guias espirituais. 
             Liderados por um ancião, o ritual atingia seu ápice, dissipando as fronteiras entre o mundo terreno e espiritual. Os Uriki acreditavam que, nesses momentos, a sabedoria ancestral era compartilhada pelos espíritos, proporcionando orientação e bênçãos para a tribo. 
             Ao nascer do sol, agradeciam aos espíritos, mantendo viva a chama da espiritualidade e harmonia com a natureza para as gerações futuras. </label>
          
        </div>
  
        <!-- Campo para o player de música -->
        <div>
          
          <audio controls class="w-full">
            <source src="../public/uriki.aac" type="audio/mpeg">
          </audio>
        </div>
        
      </div>
    </div>
  </template>