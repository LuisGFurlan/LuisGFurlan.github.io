<template>
    <div class="relative h-screen bg-primary flex   px-4">
        <div class="absolute top-[400px] left-[400px] rounded-xl  p-8 w-[600px] text-center">
            <div class="w-[550px] h-[550px] bg-indigo-500 rounded-full flex items-center justify-center">
                <img :src="foto" alt="Minha Foto"
                    class="w-[530px] h-[530px] rounded-full object-cover border-4 border-white" />
            </div>
            <!-- Nome -->
            <h2 class="mt-6 text-3xl font-bold text-white">
                dev<span class="text-indigo-500">Furlan</span>
            </h2>

            <!-- Profissão -->
            <p class="text-3xl text-indigo-600 font-medium mt-1">Desenvolvedor Mobile</p>

        </div>
       <div
  class="absolute top-[500px] left-[1400px] rounded-xl shadow-2xl text-center w-[850px] h-[500px] p-8 flex flex-col justify-between">

            <div>
                <h2 class="text-4xl font-bold text-indigo-600 text-left w-full">Sobre mim:</h2>
                <p class="text-3xl text-white font-medium mt-6">
                    Sou <span class="text-indigo-600 font-semibold">Luis Gustavo Sardo Furlan</span>, eterno estudante e desenvolvedor mobile em atuação. A paixão pela
                    programação sempre fez parte da minha vida e,
                    com a experiência prática no mercado, só aumenta espontaneamente <span class="text-indigo-600 font-semibold">:)</span></p>
            </div>
            <div>
                <p class=" text-1xl text-gray-500  mt-8">Em busca do progresso</p>
            </div>
        </div>
    </div>
</template>

<script setup>
import foto from '@/assets/images/fotoperfilPortifolio.jpg'
</script>
