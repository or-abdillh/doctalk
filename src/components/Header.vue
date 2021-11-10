<template>
    <main class="bg-primary w-full px-5 pt-4 pb-3">
        <section class="flex justify-between">
            <div class="text-gray-50 flex items-center gap-3">
                <i class="text-sm fas fa-bars"></i>
                <p class="text-xs">
                    September 29, 2021
                </p>
            </div>
            <img class="rounded" src="/profile.jpg" width="40">
        </section>

        <!-- Greetings -->
        <section class="mt-5 text-sm text-gray-50">
            <h2>Hello, Marissa</h2>
            <small>What do you need?</small>
        </section>

        <!-- Search -->
        <section class="bg-gray-50 text-xs px-3 py-2 gap-2 mt-2 flex rounded items-center">
            <i class="text-gray-400 fa fa-search"></i>
            <input type="search" class="text-xs w-full bg-gray-50" placeholder="Find a doctor or specialist">
        </section>

        <!-- Calendar -->
        <section class="mt-3 flex justify-between text-gray-50">
            <template v-for="card in 7" :key="card">
                <div class="">
                    <small class="text-xxs">Sun</small>
                    <div class="text-xs bg-blue-400  grid place-items-center">
                        {{ card + 24 }}
                    </div>
                </div>
            </template>
        </section>
    </main>
</template>

<script setup>

    import { ref } from 'vue'
 
</script>