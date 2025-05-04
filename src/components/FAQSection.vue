<script setup>
const faq = [
  {
    question: "O sistema tem período de teste?",
    answer: "Sim! Você pode testar por 7 dias gratuitamente.",
  },
  {
    question: "Funciona no celular?",
    answer: "Sim, é totalmente responsivo e funciona em qualquer dispositivo.",
  },
  {
    question: "Como cancelo a assinatura?",
    answer: "Você pode cancelar a qualquer momento pelo painel do usuário.",
  },
];
</script>

<template>
  <section class="py-16 bg-white max-w-4xl mx-auto px-4">
    <h3 class="text-2xl font-semibold text-center mb-8">
      Perguntas Frequentes
    </h3>
    <div v-for="(item, index) in faq" :key="index" class="border-b">
      <details class="py-4">
        <summary class="font-medium cursor-pointer">
          {{ item.question }}
        </summary>
        <p class="mt-2 text-sm pl-6 text-gray-700">{{ item.answer }}</p>
      </details>
    </div>
  </section>
</template>