<template>
    <div class="py-12 max-w-7xl">
        <h1 class="mt-2 text-6xl font-extrabold tracking-tight text-gray-900">
          {{ heading }}
        </h1>
        <p class="mt-4 max-w-2xl text-xl text-gray-500">
          {{ subheading }}
        </p>
    </div>
</template>

<script>
export default {
    props: {
        heading: {
            type: String,
            default: 'Page Title'
        },
        subheading: {
            type: String,
            default: 'Lorem ipsum dolor sit amet consect adipisicing elit.'
        }
    }
}
</script>
