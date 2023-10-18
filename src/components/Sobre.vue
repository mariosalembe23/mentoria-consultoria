<script setup>
import CardSobre from "./CardSobre.vue";
</script>

<template>
  <section>
    <header class="text-center">
      <h2
        class="text-2xl retrato-tablet:text-3xl font-semibold text-indigo-600"
      >
        Conheça-nos Melhor!
      </h2>
    </header>
    <aside
      class="grid p-3  gap-5 grid-cols-1 retrato-tablet:grid-cols-5 max-w-5xl w-full justify-center items-center m-auto mt-6"
    >
      <CardSobre
        tituloCard="Visão"
        tituloCor="text-indigo-600"
        conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis, eaque temporibus illo!"
        iconPath="/icons/iconVision.svg"
        classIcon="w-8 h-8"
        bgColor="bg-indigo-50 col-span-3 shadow-lg"
        textColor="text-indigo-600 font-medium"
      />
      <CardSobre
        tituloCard="Missão"
        tituloCor="text-white"
        conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis, eaque temporibus illo!"
        iconPath="/icons/iconMission.svg"
        classIcon="w-8 h-8"
        bgColor="bg-indigo-600 retrato-tablet:col-span-2 col-span-3"
        textColor="text-indigo-200 font-medium"
      />
      <CardSobre
        tituloCard="Valores"
        tituloCor="text-indigo-600"
        conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis, eaque temporibus illo!"
        iconPath="/icons/iconValores.svg"
        classIcon="w-8 h-8"
        bgColor="bg-indigo-50 shadow-lg retrato-tablet:col-span-2 col-span-3"
        textColor="text-indigo-600 font-medium"
      />
      <a href="#" class="col-span-3">
        <CardSobre
          tituloCard="História"
          tituloCor="text-white"
          conteudoCard="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo, a
        perferendis. Clique para saber mais..."
          iconPath="/icons/iconHistory.svg"
          classIcon="w-8 h-8"
          bgColor="bg-indigo-600 transition-all hover:opacity-80 "
          textColor="text-indigo-200 font-medium"
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
