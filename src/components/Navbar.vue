<template>
  <header class="bg-white shadow h-16 flex justify-between items-stretch">
    <router-link
      :to="{ name: 'home' }"
      class="inline-flex items-center h-full px-5 text-orange-500 font-bold" 
    >
    <img width="60" height="70" src="src\assets\cuchilleria.gif" alt="src\assets\cuchilleria.gif" > 
      Inicio
    </router-link>
    <div class="flex items-center gap-1">
      <router-link
        :to="{ name: 'byName' }"
        class="inline-flex items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
      >
    <img width="60" height="70" src="src\assets\buscando.png" alt="ssrc\assets\buscando.png" > 
        Buscar comidas
      </router-link>
      <router-link
        :to="{ name: 'byLetter' }"
        class="inline-flex items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
      >
    <img width="60" height="70" src="src\assets\menu-del-restaurante.png" alt="src\assets\menu-del-restaurante.png" > 
        Comidas por carta
      </router-link>
      <router-link
        :to="{ name: 'ingredients' }"
        class="inline-flex items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
      >
    <img width="60" height="70" src="src\assets\tienda-de-comestibles.png" alt="src\assets\tienda-de-comestibles.png" > 
        Comidas por ingredientes
      </router-link>
    </div>
  </header>
</template>
