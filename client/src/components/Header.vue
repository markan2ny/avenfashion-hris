<template>
    <header class="w-full py-2 shadow-md">
        <nav class="flex items-center justify-between container mx-auto">
            <router-link :to="{ name: 'login' }"
                class="font-squada text-4xl bg-gradient-to-r from-cyan-500 to-pink-500 text-transparent bg-clip-text">
                AFMI</router-link>
            <ul class="flex text-md uppercase gap-x-5">
                <li>
                    <router-link :to="{ name: 'login' }">Login</router-link>
                </li>
            </ul>
        </nav>
    </header>
</template>


<script setup>
import { RouterLink } from 'vue-router'
</script>