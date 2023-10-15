<script setup></script>

<template>
  <section class="mt-20">
    <div class="w-full grid-cols-1 grid">
      <!-- PRIMEIRO CARD -->
      <div class="w-full grid grid-cols-1 paisagem-tablet:grid-cols-2 retrato-tablet:gap-1 gpa-0 items-center">
        <div>
          <picture>
            <a href="https://storyset.com/people">
              <img src="/img/docs.png" alt="imagem-de-uma-pessoa-na-web" />
            </a>
          </picture>
        </div>
        <div class="p-4">
          <header>
            <h5 class="text-xl text-indigo-600 font-medium">
              Uma Documentação Simples
            </h5>
          </header>

          <div class="py-4">
            <p class="text-slate-800">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
              quisquam quos esse officia animi, fugit beatae, a possimus,
              voluptate ea eos. Ipsa corporis earum iste animi labore qui
              officia unde!
            </p>
            <br />
            <p class="text-slate-800">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
              quisquam quos esse officia animi, fugit beatae, a possimus,
            </p>

            <a
              href="#"
              class="inline-block mt-5 px-6 py-2 ring-2 ring-zinc-300 rounded text-[15px] font-medium text-indigo-800 transition-all hover:ring-indigo-600 hover:bg-indigo-600 hover:text-white"
            >
              Ver agora
            </a>
          </div>
        </div>
      </div>

      <!-- SEGUNDO CARD -->
      <div class="w-full grid grid-cols-1 paisagem-tablet:grid-cols-2 gap-1 items-center">
        <div>
          <picture>
            <a href="https://storyset.com/business">
              <img src="/img/status.png" alt="imagem-de-painel-de-negocios" />
            </a>
          </picture>
        </div>
        <div class="p-4 retrato-tablet:-order-1">
          <header>
            <h5 class="text-xl text-indigo-600 font-medium">
              Variedade de Informações
            </h5>
          </header>

          <div class="py-4">
            <p class="text-slate-800">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
              quisquam quos esse officia animi, fugit beatae, a possimus,
              voluptate ea eos. Ipsa corporis earum iste animi labore qui
              officia unde!
            </p>
            <br />
            <p class="text-slate-800">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab
              quisquam quos esse officia animi, fugit beatae, a possimus,
            </p>

            <a
              href="#"
              class="inline-block mt-5 px-6 py-2 bg-indigo-600 rounded text-[15px] font-medium text-white transition-all  hover:bg-indigo-700"
            >
            Inscrever-me
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
