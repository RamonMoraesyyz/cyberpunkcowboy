<template>
    <div class="relative bg-black text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="../public/steelbossa.jpg" class="w-full h-auto md:h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-12 mt-1">Bossa Nova Sunday n°5</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-4">
          <label class="text-lg">Produção: 03/03/2024</label>
          
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg block mb-2">Steel Rider, um talentoso músico que dominava o violão, era conhecido por sua habilidade única em misturar estilos musicais, especialmente bossa nova, com elementos futurísticos em suas performances. Ele começou sua carreira musical como parceiro do renomado percussionista conhecido como Bongomaster. Juntos, eles encantaram o público de nigth city com suas músicas envolventes e vibrantes.

            No entanto, como muitas parcerias, a relação entre Steel Rider e Bongomaster eventualmente se desgastou. Diferenças criativas e tensões pessoais surgiram, levando a uma separação amarga. Após a ruptura, Steel Rider decidiu seguir sua própria jornada musical.

            
            <br>
            <br>
            Determinado a continuar sua paixão pela música, Steel Rider partiu em carreira solo, levando consigo apenas seu violão e sua inigualável habilidade de criar melodias cativantes. Ele mergulhou profundamente nas raízes da bossa nova, explorando sua rica história e suas harmonias suaves. Inspirado pela solidão de suas viagens e pela beleza dos ambientes futurísticos, ele começou a compor músicas que capturavam a essência da cidade e sua própria jornada interior.

            À medida que Steel Rider viajava de cidade em cidade, suas performances solitárias atraíam uma legião de fãs ávidos por sua música autêntica e emotiva. Suas melodias suaves e ritmos cativantes transportavam o público para um mundo de sonhos, onde as fronteiras entre o passado e o futuro se misturavam harmoniosamente.


            </label>
        </div>
  
        <!-- Campo para o player de música -->
        <div class="w-full mb-4 md:mt-10">
          <audio controls class="w-full">
            <source src="../public/bossanova.mp3" type="audio/mpeg">
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