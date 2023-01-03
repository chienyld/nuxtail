<template>
    <div class="w-9/12 m-auto">
        <h1>Index</h1>
        <div class="grid grid-cols-12 gap-1">
            <input v-model="id" class="col-span-8 bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"/>
            <button class="p-2.5 col-span-4 bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-lg">
                <NuxtLink  :to="'about/'+id">Go</NuxtLink>
            </button>
        </div>
    </div>
</template>

<script setup>
let id = ref();
</script>

<style scoped>
a{
    text-decoration: none;
}
</style>