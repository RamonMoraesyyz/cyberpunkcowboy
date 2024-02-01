<template>
    <div class="relative bg-black text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="../public/skull.jpg" class="w-full h-auto md:h-full object-cover transform scale-70" />
      </div>
  
      <!-- Conteúdo direito (título, data, detalhes) -->
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <!-- Título -->
        <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-12 mt-1">Bongomaster n°4</h1>
  
        <!-- Campo para a data da produção -->
        <div class="mb-4">
          <label class="text-lg">Produção: 01/02/2024</label>
          
        </div>
  
        <!-- Campo para detalhes -->
        <div class="mb-4">
          <label class="text-lg block mb-2">Bongomaster, mestre das percussões, e Steel Rider, um guitarrista com lâminas afiadas incorporadas em sua guitarra, formaram uma parceria musical nas entranhas de Night city. 
            Tornaram-se ícones de resistência ao realizar performances em locais clandestinos, desafiando megacorporações e inspirando rebeldes por meio de músicas que denunciavam a opressão e buscavam a liberdade. 
            Sua lenda cresceu, propagando-se secretamente pela sociedade, enquanto Bongomaster e Steel Rider permanecem dedicados a usar a música como arma contra as forças obscuras que dominam a cidade distópica.
            <br>
            <br>
            À medida que a fama dos artistas crescia, também aumentavam os riscos associados às suas performances clandestinas. 
            Megacorporações tentavam silenciá-los, considerando-os uma ameaça à estabilidade controlada pela tecnocracia. No entanto, Bongomaster e Steel Rider continuaram a desafiar as autoridades, atraindo a atenção não apenas dos oprimidos, mas também de grupos de resistência que viam na música dos artistas uma poderosa ferramenta de mobilização. 
            O dueto, agora conhecido como os "Sons da Revolta", tornou-se um símbolo de esperança e inspiração, desafiando as forças opressivas enquanto navegavam pelas sombras de Nigth city, 
            deixando uma marca indelével na história da resistência musical.


</label>
        </div>
  
        <!-- Campo para o player de música -->
        <div class="w-full mb-4 md:mt-10">
          <audio controls class="w-full">
            <source src="../public/bongomaster.mp3" type="audio/mpeg">
          </audio>
        </div>
        
      </div>
    </div>
  </template>