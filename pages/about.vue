<template>
    <div>
      <Navigation />
      <Hero title="About" />

      <div class="py-10">
          <h2 class="text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Team</h2>
          <p class="mt-2 text-gray-500 max-w-3xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pretium nibh non lacus fermentum posuere. Mauris eu velit lectus. Interdum et malesuada fames ac ante ipsum primis in faucibus.</p>
          <Table/>
      </div>

      <div class="py-10">
          <h2 class="text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Blog</h2>
          <p class="mt-2 mb-8 text-gray-500 max-w-3xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pretium nibh non lacus.</p>
          <nuxt-link to="/blog" class="mr-2 px-4 py-2 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700">
              Visit Blog
          </nuxt-link>
      </div>
    </div>
</template>