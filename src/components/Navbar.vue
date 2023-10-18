<script setup>
window.addEventListener("load", () => {
  const navbar = document.querySelector(".navbar");

  if (!navbar) {
    return;
  }

  const ScrollPage = () => {
    if (window.scrollY === 0) {
      navbar.classList.remove("shadow-lg");
      navbar.classList.remove("border-b");
    } else {
      navbar.classList.add("shadow-lg");
      navbar.classList.add("border-b");
    }
  };

  ScrollPage();

  document.addEventListener("scroll", ScrollPage);
});

function showOffCanvas() {
  const backgroundContainer = document.querySelector(".background");
  const offCanvas = document.querySelector(".offcanvas");
  backgroundContainer.classList.remove("hidden");
  backgroundContainer.classList.add("lowEffect");

  offCanvas.classList.add("visibleOffCanvas");
}
</script>

<template>
  <div
    class="navbar w-full transition-all ease-in-out fixed top-0 left-0 right-0 z-30 border-indigo-400 bg-indigo-600 py-4 paisagem-tablet:px-7 flex items-center paisagem-tablet:justify-around justify-between px-4"
  >
    <div>
      <a
        href="#"
        class="text-indigo-200 text-[1.18rem] font-semibold"
        title="Logotipo"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-6 h-6 stroke-2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5"
          />
        </svg>
      </a>
    </div>
    <div>
      <nav>
        <ul class="flex items-center paisagem-tablet:space-x-6 space-x-4">
          <li class="paisagem-tablet:inline-block hidden">
            <a
              href="#"
              class="text-indigo-100 text-[14px] font-medium transition-all hover:text-white"
              >Documentários</a
            >
          </li>
          <li class="paisagem-tablet:inline-block hidden">
            <a
              href="#"
              class="text-indigo-100 text-[14px] font-medium transition-all hover:text-white"
              >Formações</a
            >
          </li>
          <li class="paisagem-tablet:inline-block hidden">
            <a
              href="#"
              class="text-indigo-100 text-[14px] font-medium transition-all hover:text-white"
              >Consultorias</a
            >
          </li>
          <li class="paisagem-tablet:inline-block hidden">
            <a
              href="#"
              class="text-indigo-100 text-[14px] font-medium transition-all hover:text-white"
              >Ndengue</a
            >
          </li>

          <button
            class="hover:text-indigo-300 paisagem-tablet:ps-4 paisagem-tablet:border-l border-indigo-400 transition-all text-white"
            title="Pesquisar"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6 stroke-2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"
              />
            </svg>
          </button>

          <li class="paisagem-tablet:inline-block hidden">
            <a
              href="#"
              class="hover:text-indigo-300 transition-all text-white"
              title="E-mail"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6 stroke-2"
              >
                <path
                  stroke-linecap="round"
                  d="M16.5 12a4.5 4.5 0 11-9 0 4.5 4.5 0 019 0zm0 0c0 1.657 1.007 3 2.25 3S21 13.657 21 12a9 9 0 10-2.636 6.364M16.5 12V8.25"
                />
              </svg>
            </a>
          </li>
          <li class="paisagem-tablet:inline-block hidden">
            <a
              href="#"
              class="hover:text-indigo-300 transition-all text-white"
              title="Comunidade"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6 stroke-2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.031c0 .225-.012.447-.037.666A11.944 11.944 0 0112 21c-2.17 0-4.207-.576-5.963-1.584A6.062 6.062 0 016 18.719m12 0a5.971 5.971 0 00-.941-3.197m0 0A5.995 5.995 0 0012 12.75a5.995 5.995 0 00-5.058 2.772m0 0a3 3 0 00-4.681 2.72 8.986 8.986 0 003.74.477m.94-3.197a5.971 5.971 0 00-.94 3.197M15 6.75a3 3 0 11-6 0 3 3 0 016 0zm6 3a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0zm-13.5 0a2.25 2.25 0 11-4.5 0 2.25 2.25 0 014.5 0z"
                />
              </svg>
            </a>
          </li>

          <button
            @click="showOffCanvas"
            class="hover:text-indigo-300 transition-all text-white paisagem-tablet:hidden inline-block"
            title="menu"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6 stroke-2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 6.75a.75.75 0 110-1.5.75.75 0 010 1.5zM12 12.75a.75.75 0 110-1.5.75.75 0 010 1.5zM12 18.75a.75.75 0 110-1.5.75.75 0 010 1.5z"
              />
            </svg>
          </button>
        </ul>
      </nav>
    </div>
  </div>
</template>

<style scoped></style>
