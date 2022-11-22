<template>
  <section>
    <div
      class="h-screen grid grid-cols-1 lg:grid-cols-2 gap-6 place-items-center pl-10 pr-10 pt-16"
    >
      <div>
        <img src="../assets/images/404.png" class="bg-gray-600 p-10" />
      </div>
      <div>
        <div>
          <h1 class="text-gray-800 font-bold text-4xl">
            Oops, this page doesn't exist! Test
          </h1>
          <p class="text-gray-800 text-2xl">
            Sorry about that! It might have been moved or deleted.
          </p>
          <div class="py-5">
            <router-link
              to="/"
              class="text-xl py-4 px-8 rounded text-center bg-gray-600 hover:bg-gray-700 text-white"
              >Home</router-link
            >
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
