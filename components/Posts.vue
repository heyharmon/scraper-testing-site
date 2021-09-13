<template>
    <div class="mt-6 grid grid-cols-1 gap-y-10 gap-x-4 sm:grid-cols-2 lg:grid-cols-3 xl:gap-x-6">
      <div v-for="post in posts" class="group relative">
        <div class="w-full min-h-80 bg-gray-200 aspect-w-1 aspect-h-1 rounded-md overflow-hidden group-hover:opacity-75 lg:h-80 lg:aspect-none">
          <img :src="post.img" alt="Front of men&#039;s Basic Tee in black." class="w-full h-full object-center object-cover lg:w-full lg:h-full">
        </div>
        <div class="mt-4">
          <div>
            <p class="mb-1 text-sm text-gray-500">Category</p>
            <h3 class="text-lg font-extrabold tracking-tight text-gray-900">
              <nuxt-link :to="post.url">
                <span aria-hidden="true" class="absolute inset-0"></span>
                {{ post.title }}
            </nuxt-link>
            </h3>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            posts: [
                {
                    'img': 'https://images.unsplash.com/photo-1573164713988-8665fc963095?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1050&q=80',
                    'title': 'The Future According to Technology Experts',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1586920740199-47ce35183cfd?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1489&q=80',
                    'title': 'The Rise of Machine Learning and How to Make It Stop',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1555949963-ff9fe0c870eb?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80',
                    'title': 'Starting Conversations With Your Kids About Machine Learning',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1052&q=80',
                    'title': 'Think You Know Machine Learning? Think Again',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80',
                    'title': 'The Most Boring Article About Artificial Intelligence You\'ll Ever Read',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80',
                    'title': 'Let’s Admit It: Everyone Secretly Hates Technology',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80',
                    'title': 'What the World Would Be Like If technology Didn\'t Exist',
                    'url': '#'
                },
                {
                    'img': 'https://images.unsplash.com/photo-1581090700227-1e37b190418e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80',
                    'title': 'Ways Your Mother Lied to You About technology',
                    'url': '#'
                }
            ]
        }
    }
}
</script>
