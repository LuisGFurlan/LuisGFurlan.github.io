<template>
    <div class="relative h-screen bg-primary flex items-center justify-center px-4">
        <div class="w-[75%] h-[75%]  rounded-xl shadow-lg p-8 flex items-center justify-center">
            <div class="flex justify-between gap-6 w-full">
                <!-- Projeto 1 -->
                <div class="bg-indigo-100 rounded-lg p-4 w-[30%] h-[800px] flex flex-col justify-between">
                    <div class="h-1/2 bg-gray-300 rounded-md overflow-hidden mb-4">
                        <img :src="fotoProjeto1" alt="Imagem Projeto 1" class="w-full h-full object-cover" />

                    </div>

                    <!-- Descrição abaixo -->
                    <div>
                        <h3 class="text-2xl text-indigo-600 font-semibold">Integração com API e Firebase</h3>
                        <p class="text-1xl text-gray-700 mt-2">Aplicativo criado para praticar lógica com Flutter,
                            integrar o Firebase e consumir APIs externas, como uma API de CEP. O projeto foi essencial
                            para entender na prática conceitos de backend e fortalecer o uso de integrações reais com
                            Flutter.</p>
                    </div>
                </div>


                <!-- Projeto 2 -->
                <div class="bg-indigo-100 rounded-lg p-4 w-[30%] h-[800px] flex flex-col justify-between">
                    <div class="h-1/2 bg-gray-300 rounded-md overflow-hidden mb-4">
                        <img :src="fotoProjeto2" alt="Imagem Projeto 1" class="w-full h-full object-cover" />
                    </div>

                    <!-- Descrição abaixo -->
                    <div>
                        <h3 class="text-2xl text-indigo-600 font-semibold">Lista de Contatos</h3>
                        <p class="text-1xl text-gray-700 mt-2">Este app foi desenvolvido utilizando exclusivamente
                            widgets nativos do Flutter. A intenção foi aprofundar o conhecimento na linguagem, melhorar
                            a familiaridade com a estrutura de código e consolidar a base da construção de interfaces
                            sem dependências externas.</p>
                    </div>
                </div>

                <!-- Projeto 3 -->
                <div class="bg-indigo-100 rounded-lg p-4 w-[30%] h-[800px] flex flex-col justify-between">
                    <div class="h-1/2 bg-gray-300 rounded-md overflow-hidden mb-4">
                        <img :src="fotoProjeto3" alt="Imagem Projeto 1" class="w-full h-full object-cover" />
                    </div>

                    <!-- Descrição abaixo -->
                    <div>
                        <h3 class="text-2xl text-indigo-600 font-semibold">Lista de Tarefas</h3>
                        <p class="text-1xl text-gray-700 mt-2">Meu primeiro contato com Flutter. Apesar da simplicidade,
                            esse app foi fundamental para despertar minha paixão por desenvolvimento mobile. Nele, dei
                            os primeiros passos com widgets, estado e navegação, marcando o início da minha jornada como
                            dev.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import fotoProjeto1 from '@/assets/images/FirebaseFlutter.jpg'
import fotoProjeto2 from '@/assets/images/ListadeContatosFlutter.jpg'
import fotoProjeto3 from '@/assets/images/ListadeTarefasFlutter.jpg'
</script>