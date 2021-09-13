<template>
    <header class="mx-auto">
      <div class="flex justify-between items-center border-b-2 border-gray-100 py-6 md:justify-start md:space-x-10">
        <!-- Logo -->
        <div class="flex justify-start lg:w-0 lg:flex-1">
          <nuxt-link to="/">
            <span class="sr-only">Scraper Test Site</span>
            <img class="h-8 w-auto sm:h-10" src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg" alt="">
          </nuxt-link>
        </div>

        <nav class="hidden md:flex space-x-10">
          <nuxt-link to="/about" class="text-base font-medium text-gray-500 hover:text-gray-900">
              About
          </nuxt-link>
          <nuxt-link to="/pricing" class="text-base font-medium text-gray-500 hover:text-gray-900">
            Pricing
          </nuxt-link>
          <nuxt-link to="/blog" class="text-base font-medium text-gray-500 hover:text-gray-900">
            Blog
          </nuxt-link>
        </nav>

        <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
          <nuxt-link to="/contact" class="ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-indigo-600 hover:bg-indigo-700">
            Contact
          </nuxt-link>
        </div>
      </div>
  </header>
</template>
