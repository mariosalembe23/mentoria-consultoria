<script setup>
import CardSobre from "./CardSobre.vue";
</script>

<template>
  <section>
    <header class="text-center">
      <h2 class="text-2xl retrato-tablet:text-3xl font-semibold text-indigo-600">
        Conheça-nos Melhor!
      </h2>
    </header>
    <aside
      class="grid text-indigo-200 gap-5 grid-cols-1 retrato-tablet:grid-cols-2 max-w-2xl w-full justify-center items-center m-auto mt-6"
    >
      <CardSobre
        tituloCard="Visão"
        tituloCor="text-white"
        conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis, eaque temporibus illo!"
        iconPath="/icons/iconVision.svg"
        classIcon="w-8 h-8"
        bgColor="bg-indigo-600"
        textColor="text-indigo-200"
      />
      <CardSobre
        tituloCard="Missão"
        tituloCor="text-white"
        conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis, eaque temporibus illo!"
        iconPath="/icons/iconMission.svg"
        classIcon="w-8 h-8"
        bgColor="bg-indigo-600"
        textColor="text-indigo-200"
      />
      <CardSobre
        tituloCard="Valores"
        tituloCor="text-indigo-600"
        conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis, eaque temporibus illo!"
        iconPath="/icons/iconValores.svg"
        classIcon="w-8 h-8"
        bgColor="bg-indigo-50 shadow-lg"
        textColor="text-indigo-600"
      />
      <a href="#">
        <CardSobre
          tituloCard="História"
          tituloCor="text-white"
          conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis. Clique para saber mais..."
          iconPath="/icons/iconHistory.svg"
          classIcon="w-8 h-8"
          bgColor="bg-indigo-600 transition-all hover:opacity-80"
          textColor="text-indigo-200"
        />
      </a>
    </aside>
  </section>
</template>

<style>
i {
  background-color: #4f46e5;
}
</style>
