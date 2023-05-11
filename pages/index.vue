<template>
    <div>
      <Navigation />
      <Hero title="Homepage" />

      <div class="py-10">
          <h2 class="text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">About</h2>
          <p class="mt-2 mb-8 text-gray-500 max-w-3xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pretium nibh non lacus.</p>
          <nuxt-link to="/about" class="mr-2 px-4 py-2 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700">
              About Us
          </nuxt-link>
      </div>

      <div class="py-10">
          <h2 class="text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Resources</h2>
          <p class="mt-2 mb-8 text-gray-500 max-w-3xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pretium nibh non lacus.</p>
          <a href="https://google.com" target="_blank" class="mr-2 px-4 py-2 border border-transparent text-base font-medium rounded-md text-indigo-700 bg-indigo-100 hover:bg-indigo-200">
              External Link [Google]
          </a>
          <a href="/pdf-file.pdf" class="mr-2 px-4 py-2 border border-transparent text-base font-medium rounded-md text-indigo-700 bg-indigo-100 hover:bg-indigo-200">
              Absolute Link [PDF]
          </a>
      </div>
    </div>
</template>
