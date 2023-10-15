<script setup>
import CardImage from "./CardImage.vue";
</script>

<template>
  <section class="mt-10">
    <header class="text-center">
      <h2
        class="text-2xl retrato-tablet:text-3xl font-semibold text-indigo-600"
      >
        Receba Formações Totalmente Grátis!
      </h2>
    </header>
    <div class="text-center retrato-tablet:w-4/5 w-full m-auto py-2">
      <p class="text-slate-800">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus
        eveniet tempore ut laudantium, molestias sint quos tenetur ipsam culpa
        maxime, magnam officia, error dolores sed iste incidunt ducimus in.
        Sunt?
      </p>
    </div>

    <!-- CARDS -->
    <aside
      class="max-w-3xl gap-3 mx-auto w-full  grid grid-cols-1 retrato-tablet:grid-cols-2 mt-4 items-center justify-center"
    >
      <CardImage
        urlBackImg="bg-[url('/img/disciplina.jpg')]"
        titleCard="Disciplina"
        textSmall="Velamos Pela Disciplina e Bom Senso!"
        iconPath="/icons/disciplina.svg"
        descImg="icone-de-disciplina"
      />
      <CardImage
        urlBackImg="bg-[url('/img/compromisso.jpg')]"
        titleCard="Compromisso"
        textSmall="Siga Confiante em nossos Passos!"
        iconPath="/icons/compromisso.svg"
        descImg="icone-de-chave-compromisso"
      />
      <CardImage
        urlBackImg="bg-[url('/img/desenvolvimento.jpg')]"
        titleCard="Desenvolvimento"
        textSmall="Juntos Lapidaremos sua Jornada!"
        iconPath="/icons/desenvolvimento.svg"
        descImg="icone-de-foguete-desenvolvimento"
      />
      <a href="#">
        <div
          class="h-96 bg-indigo-600 rounded p-5 flex flex-col justify-between hover:bg-indigo-800 transition-all"
        >
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-7 h-7 stroke-indigo-100 stroke-2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0112 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 016 18.719m12 0a5.971 5.971 0 00-.941-3.197m0 0A5.995 5.995 0 0012 12.75a5.995 5.995 0 00-5.058 2.772m0 0a3 3 0 00-4.681 2.72 8.986 8.986 0 003.74.477m.94-3.197a5.971 5.971 0 00-.94 3.197M15 6.75a3 3 0 11-6 0 3 3 0 016 0zm6 3a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0zm-13.5 0a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0z"
              />
            </svg>
          </div>
          <div>
            <h5 class="text-xl font-medium text-white">
              Inicie Agora a Formação
            </h5>
            <small class="text-indigo-100 font-medium">
              Junte-se á Comunidade de Membros que já se Cadastraram e Aperte os
              sintos para seu Desenvolviemto!
            </small>

            <br />
            <small class="text-white">Dê um Clique neste Quadro...</small>
          </div>
        </div>
      </a>
    </aside>
    <div class="text-center">
      <a
        href="#"
        class="inline-block mt-5 px-6 py-2 bg-indigo-600 rounded text-[15px] font-medium text-white transition-all hover:bg-indigo-700"
      >
        Iniciar Formação
      </a>
    </div>
  </section>
</template>

<style scoped></style>
