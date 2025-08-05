<template>
  <section
    id="about"
    class="relative h-screen bg-primary flex items-center justify-center px-4 scroll-mt-28"
  >
    <!-- Container geral -->
    <div class="w-full h-full relative">
      <!-- Card da foto -->
      <div
        class="absolute left-1/2 transform -translate-x-1/2 top-[140px] md:top-[150px] md:left-[200px] md:translate-x-0 rounded-xl text-center"
      >
        <div
          class="w-[200px] h-[200px] md:w-[550px] md:h-[550px] bg-indigo-500 rounded-full flex items-center justify-center mx-auto md:mx-0"
        >
          <img
            :src="foto"
            alt="Minha Foto"
            class="w-[180px] h-[180px] md:w-[530px] md:h-[530px] rounded-full object-cover border-4 border-white"
          />
        </div>
        <!-- Nome -->
        <h2 class="mt-2 text-2xl md:text-3xl font-bold text-white">
          dev<span class="text-indigo-500">Furlan</span>
        </h2>
        <!-- Profissão -->
        <p class="text-xl text-indigo-600 font-medium mt-1 hidden md:block">
          Desenvolvedor Mobile
        </p>
      </div>

      <!-- Texto -->
      <div
        class="absolute left-1/2 transform -translate-x-1/2 top-[340px] md:top-[180px] md:left-[900px] md:translate-x-0 w-[450px] md:w-[850px] h-[500px] rounded-xl shadow-2xl p-8 md:p-14 flex flex-col justify-between text-center md:text-left"
      >
        <div>
          <h2
            class="hidden md:block text-4xl font-bold text-indigo-600 w-full"
          >
            Sobre mim:
          </h2>
          <p
            class="text-xl md:text-3xl text-white font-medium mt-6 md:mt-6"
          >
            <span class="md:hidden">Prazer!</span> Sou
            <span class="text-indigo-500 md:text-indigo-600 font-semibold"
              >Luis Gustavo Sardo Furlan</span
            >, eterno estudante e
            <span class="text-indigo-500 md:text-indigo-600 font-semibold"
              >Desenvolvedor mobile</span
            >
            em atuação. A paixão pela programação sempre fez parte da minha
            vida e, com a experiência prática no mercado, só aumenta
            espontaneamente
            <span class="text-indigo-500 md:text-indigo-600 font-semibold"
              >:)</span
            >
          </p>
        </div>
        <div>
          <p class="text-xl text-gray-500 mt-8">Em busca do progresso</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import foto from '@/assets/images/fotoperfilPortifolio.jpg'
</script>
