

<template layout>

    <h1 class="text-4xl text-blue-1000">Hello World!!!</h1>


</template>

<script setup>

import { Link, usePage } from '@inertiajs/inertia-vue3'

const props = defineProps({
    topics:Array
})

const message = "This is a vue page."

const user = usePage().props.auth

console.log(user)

</script>
