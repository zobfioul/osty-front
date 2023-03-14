<script>
export default {
  props: ['title', 'url']
}
</script>

<template>
    <li>
        <NuxtLink v-bind:to="url" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
            <slot></slot>
            <span class="ml-3">{{ title }}</span>
        </NuxtLink>
    </li>
</template>