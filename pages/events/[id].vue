<template>
    <div>
        <!-- [] for dynamic routes -->
        event id: {{ $route.params.id }}
    </div>
</template>


<script setup>

const nuxt = useNuxtApp();
const route = useRoute();
console.log(route.params)
console.log(nuxt)


</script>