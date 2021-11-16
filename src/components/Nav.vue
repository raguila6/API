<template>
  <div class="text-green-200 bg-green-800">
    <div class="container flex items-center justify-between mx-auto">
      <h1 class="text-3xl font-thin tracking-tighter">
        <span class="font-normal">API</span>
      </h1>
      <nav>
        <ul class="flex space-x-4">
          <router-link to="/">
            <li
              class="px-4 py-8  hover:cursor-pointer hover:bg-green-500 hover:text-green-800"
            >
              Home
            </li>
          </router-link>
          <router-link :to="{ name: 'About' }">
            <li
              class="px-4 py-8  hover:cursor-pointer hover:bg-green-500 hover:text-green-800"
            >
              About
            </li>
          </router-link>
          <router-link :to="{ path: '/hello', name: 'Hello' }">
            <li
              class="px-4 py-8  hover:cursor-pointer hover:bg-green-500 hover:text-green-800"
            >
              Hello
            </li>
          </router-link>
        </ul>
      </nav>
    </div>
  </div>
</template>
