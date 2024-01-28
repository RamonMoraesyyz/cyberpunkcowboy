<template>
    <div class="relative bg-black text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="../public/spider.jpeg" class="w-full h-auto md:h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-10 mt-1">Lady Spider n°3</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-10">
          <label class="text-lg">Produção: 27/01/2024</label>
          
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg block mb-2">Em um laboratório secreto, uma experiência militar resulta na criação acidental de Lady Spider, uma aranha gigante mutante. 
            Ela escapa, destrói uma cidade e desafia as forças militares. 
            Cientistas desenvolvem um antídoto, revertendo as mutações e neutralizando a ameaça. 
            A cidade sofre danos irreparáveis, destacando os perigos de experimentos descontrolados. 
            Ms Spider torna-se um símbolo das consequências trágicas da pesquisa sem regulamentação.
            Apesar da reversão bem-sucedida das mutações, a cidade enfrenta um longo período de reconstrução. 
            O incidente destaca a necessidade urgente de regulamentações mais rígidas na pesquisa científica, deixando Ms Spider como um lembrete sombrio dos perigos inerentes à busca do poder sem limites.</label>
        </div>
  
        <!-- Campo para o player de música -->
        <div class="w-full mb-4 md:mt-10">
          <audio controls class="w-full">
            <source src="../public/spider.mp3" type="audio/mpeg">
          </audio>
        </div>
        
      </div>
    </div>
  </template>