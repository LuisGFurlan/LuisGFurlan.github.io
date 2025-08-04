<template>
    <div class="h-screen bg-primary flex items-center justify-center px-4">
        <div class="flex flex-wrap justify-center gap-8 w-full">
            <div class="bg-white rounded-xl shadow-lg p-8 max-w-sm text-center">

                <div class="flex justify-center">
                    <div class="p-2 bg-indigo-500 rounded-full">
                        <img :src="foto" alt="Minha Foto"
                            class="w-32 h-32 rounded-full object-cover border-4 border-white" />
                    </div>
                </div>

                <!-- Nome -->
                <h2 class="mt-4 text-2xl font-bold text-gray-800">Luis Furlan</h2>

                <!-- Profissão -->
                <p class="text-indigo-600 font-medium mt-1">Full Stack Developer</p>

                <!-- Skills -->
                <div class="flex flex-wrap justify-center gap-2 mt-4">
                    <span class="bg-indigo-100 text-indigo-700 text-sm px-3 py-1 rounded-full">Dart</span>
                    <span class="bg-indigo-100 text-indigo-700 text-sm px-3 py-1 rounded-full">Flutter</span>
                    <span class="bg-indigo-100 text-indigo-700 text-sm px-3 py-1 rounded-full">Tailwind CSS</span>
                    <span class="bg-indigo-100 text-indigo-700 text-sm px-3 py-1 rounded-full">PHP</span>
                </div>

            </div>
            <div class="bg-white rounded-xl shadow-lg text-center w-[350px] h-[500px] p-8 flex flex-col justify-between">
  <div>
    <h2 class="text-2xl font-bold text-gray-800">Luis G. S. Furlan</h2>
    <p class="text-indigo-600 font-medium mt-1">Full Stack Developer</p>
  </div>
  <div>
    <p class="text-gray-500 text-sm mt-8">Esse card tem altura e largura definidas 😉</p>
  </div>
</div>

        </div>
    </div>
</template>

<script setup>
import foto from '@/assets/images/fotoperfilPortifolio.jpg'
</script>
