<script setup></script>
<template>
    <nav class="bg-slate-900 px-4 text-white">
        <div class="flex justify-between items-center p-4">
            <div class="flex gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M3.75 13.5l10.5-11.25L12 10.5h8.25L9.75 21.75 12 13.5H3.75z" />
                </svg>
                <h2 class="font-bold tracking-wide text-lg">
                    <router-link to="/">Navigation</router-link>
                </h2>
            </div>
            <div class="flex gap-4 text-lg font-semibold tracking-wide">
                <router-link to="/" exact active-class="active-link">Home</router-link>
                <router-link to="/about" exact active-class="active-link">About</router-link>
                <router-link to="/contact" exact active-class="active-link">Contact</router-link>
            </div>
            <div class="flex gap-4">
                <router-link to="/signin">
                    <button class="border border-blue-500 py-2 px-4 rounded-xl text-blue-500 font-semibold
                    hover:bg-blue-500 hover:text-white ease-in-out duration-400">
                        Sign In
                    </button>
                </router-link>
                <router-link to="/signup">
                    <button class="bg-blue-600 text-white py-2 px-4 rounded-xl font-semibold
                    hover:bg-blue-700 ease-in-out duration-400">
                        Sign Up
                    </button>
                </router-link>
            </div>
        </div>
    </nav>
</template>
