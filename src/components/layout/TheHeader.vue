<template>
  <header class="sticky w-screen">
    <nav class="bg-white w-screen shadow">
      <div
        class="flex justify-between items-center text-gray-700"
      >
        <p class="pl-4 py-4 text-xl font-bold">Thomas Schwabauer</p>
        <ul
          class="hidden md:flex center pr-10 text-base font-semibold cursor-pointer"
        >
          <li class="hover:bg-gray-200 py-4 px-6">
            <a href="#landing">Home</a>
          </li>
          <li class="hover:bg-gray-200 py-4 px-6">Services</li>
          <li class="hover:bg-gray-200 py-4 px-6">
            <a href="#page4">About me</a>
          </li>
        </ul>
        <button
          class="block md:hidden py-3 px-4 mx-2 rounded focus:outline-none hover:bg-gray-200 group"
        >
          <div class="w-5 h-1 bg-gray-600 mb-1"></div>
          <div class="w-5 h-1 bg-gray-600 mb-1"></div>
          <div class="w-5 h-1 bg-gray-600"></div>
          <div
            class="absolute top-0 -right-full h-screen w-8/12 bg-white border opacity-0 group-focus:right-0 group-focus:opacity-100 transition-all duration-300"
          >
            <ul
              class="flex flex-col items-center w-full text-base cursor-pointer pt-10"
            >
              <li class="hover:bg-gray-200 py-4 px-6 w-full">Home</li>
              <li class="hover:bg-gray-200 py-4 px-6 w-full">Services</li>
              <li class="hover:bg-gray-200 py-4 px-6 w-full">About me</li>
            </ul>
          </div>
        </button>
      </div>
    </nav>
  </header>
</template>
