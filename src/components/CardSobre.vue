<script setup>
defineProps({
  tituloCard: String,
  tituloCor: String,
  conteudoCard: String,
  iconPath: String,
  classIcon: String,
  bgColor: String,
  textColor: String
});
</script>

<template>
  <div class=" p-5 h-80 rounded-lg flex flex-col justify-between select-none" :class="bgColor">
    <div>
      <img :src="iconPath" :class="classIcon" alt="icone-de-ilustração-de-visão" />
    </div>
    <div>
      <h6 class=" font-medium text-xl" :class="tituloCor">{{ tituloCard }}</h6>
      <p class="py-2 text-[14px]" :class="textColor">
        {{ conteudoCard }}
      </p>
    </div>
  </div>
</template>
