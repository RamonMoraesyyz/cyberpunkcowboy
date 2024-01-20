<template>
    <div class="relative bg-black text-white flex flex-col items-center justify-center h-screen overflow-hidden">
      <div class="flex items-center justify-center">
        <h1 class="text-4xl font-bold mb-4 mt-12">Cyberpunk cowboy n°1</h1>
      </div>
      <img src="/cyberpunkcowboy.png" class="w-100 h-full object-cover transform scale-70" />
      
       <!-- Player de música na parte inferior -->
       <div class="fixed bottom-0 w-full flex justify-center">
           <audio controls>
           <source src="../public/cyberpunkcowboyn1110124.mp3" type="audio/mpeg">
           </audio>
       </div>
    </div>
 </template>