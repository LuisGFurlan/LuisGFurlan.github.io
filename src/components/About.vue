<template>
  <section
    id="about"
    class="relative min-h-screen bg-primary flex items-center justify-center px-4 scroll-mt-28 pt-[104px]"
  >
    <div class="w-full h-full flex flex-col items-center justify-center md:flex-row md:justify-around">

      <!-- Foto, Nome e Profissão -->
      <div class="text-center md:text-center flex flex-col items-center">
        <div
          class="w-[200px] h-[200px] md:w-[400px] md:h-[400px] bg-indigo-500 rounded-full flex items-center justify-center"
        >
          <img
            :src="foto"
            alt="Minha Foto"
            class="w-[180px] h-[180px] md:w-[380px] md:h-[380px] rounded-full object-cover border-4 border-white"
          />
        </div>
        <h2 class="mt-2 text-2xl md:text-3xl font-bold text-white">
          dev<span class="text-indigo-500">Furlan</span>
        </h2>
        <p class="text-xl text-indigo-600 font-medium mt-1">
          Desenvolvedor Mobile
        </p>
      </div>

      <!-- Texto "Sobre mim" -->
      <div class=" md:mt-0 md:w-[600px] text-center md:text-left">
        <h2 class="hidden md:block text-4xl font-bold text-indigo-600 w-full">
          Sobre mim:
        </h2>
        <p class="text-xl md:text-2xl text-white font-medium mt-6">
          <span class="md:hidden">Prazer!</span> Sou
          <span class="text-indigo-500 md:text-indigo-600 font-semibold">Luis Gustavo Sardo Furlan</span>,
          eterno estudante e
          <span class="text-indigo-500 md:text-indigo-600 font-semibold">Desenvolvedor mobile</span> em atuação.
          A paixão pela programação sempre fez parte da minha vida e, com a experiência prática no mercado,
          só aumenta espontaneamente
          <span class="text-indigo-500 md:text-indigo-600 font-semibold">:)</span>
        </p>
      </div>

    </div>
  </section>
</template>

<script setup>
import foto from '@/assets/images/fotoperfilPortifolio.jpg'
</script>
