<script setup>
defineProps({
  urlBackImg: String,
  titleCard: String,
  textSmall: String,
  iconPath: String,
  descImg: String
});
</script>

<template>
  <div class="cardImage  h-96 rounded-lg" :class="urlBackImg">
    <div
      class="mask bg-[rgba(0,0,0,0.7)] w-full h-full flex flex-col justify-between p-4 rounded-lg"
    >
      <div>
        <img :src="iconPath" class="w-7 h-7 text-indigo-500" :alt="descImg">
      </div>
      <div>
        <h6 class="text-white font-medium">{{ titleCard}}</h6>
        <small class="text-white font-medium">{{ textSmall }}</small>
      </div>
    </div>
  </div>
</template>

<style scoped>
.cardImage {
  background-size: cover;
  background-position: center center;
  color: #6366f1;
}
</style>
