<template>
  <section id="projects" class="relative bg-primary flex items-center justify-center px-4 py-12">
    <div class="w-[90%] rounded-xl shadow-lg p-4 md:p-8">
      <div class="flex flex-col gap-10 md:flex-row md:justify-between md:gap-6 w-full">
        
        <!-- Projeto 1 -->
        <div class="bg-indigo-100 rounded-lg p-4 w-full h-[520px] md:w-[30%] md:h-[800px] flex flex-col justify-between">
          <div class="h-1/2 bg-gray-300 rounded-md overflow-hidden mb-4">
            <img :src="fotoProjeto1" alt="Imagem Projeto 1" class="w-full h-full object-cover" />
          </div>
          <div>
            <h3 class="text-2xl text-indigo-600 font-semibold">Integração com API e Firebase</h3>
            <p class="text-base text-gray-700 mt-2 md:text-xl">
              Aplicativo criado para praticar lógica com Flutter, integrar o Firebase e consumir APIs externas, como uma API de CEP. O projeto foi essencial para entender na prática conceitos de backend e fortalecer o uso de integrações reais com Flutter.
            </p>
          </div>
        </div>

        <!-- Projeto 2 -->
        <div class="bg-indigo-100 rounded-lg p-4 w-full h-[520px] md:w-[30%] md:h-[800px] flex flex-col justify-between">
          <div class="h-1/2 bg-gray-300 rounded-md overflow-hidden mb-4">
            <img :src="fotoProjeto2" alt="Imagem Projeto 2" class="w-full h-full object-cover" />
          </div>
          <div>
            <h3 class="text-2xl text-indigo-600 font-semibold">Lista de Contatos</h3>
            <p class="text-base text-gray-700 mt-2 md:text-xl">
              Este app foi desenvolvido utilizando exclusivamente widgets nativos do Flutter. A intenção foi aprofundar o conhecimento na linguagem, melhorar a familiaridade com a estrutura de código e consolidar a base da construção de interfaces sem dependências externas.
            </p>
          </div>
        </div>

        <!-- Projeto 3 -->
        <div class="bg-indigo-100 rounded-lg p-4 w-full h-[520px] md:w-[30%] md:h-[800px] flex flex-col justify-between">
          <div class="h-1/2 bg-gray-300 rounded-md overflow-hidden mb-4">
            <img :src="fotoProjeto3" alt="Imagem Projeto 3" class="w-full h-full object-cover" />
          </div>
          <div>
            <h3 class="text-2xl text-indigo-600 font-semibold">Lista de Tarefas</h3>
            <p class="text-base text-gray-700 mt-2 md:text-xl">
              Meu primeiro contato com Flutter. Apesar da simplicidade, esse app foi fundamental para despertar minha paixão por desenvolvimento mobile. Nele, dei os primeiros passos com widgets, estado e navegação, marcando o início da minha jornada como dev.
            </p>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script setup>
import fotoProjeto1 from '@/assets/images/FirebaseFlutter.jpg'
import fotoProjeto2 from '@/assets/images/ListadeContatosFlutter.jpg'
import fotoProjeto3 from '@/assets/images/ListadeTarefasFlutter.jpg'
</script>
