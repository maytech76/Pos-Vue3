<script setup>
 import Link from './Link.vue';
</script>

<template>
    <header class="px-10 py-5 bg-gray-700 flex lg:justify-between absolute top-0 w-full z-10">
        <div>
            <h2 class="text-3xl font-black text-white">
                POS 
            <span class="text-orange-400">
              Vue.js
            </span>
           </h2>
        </div>
        <nav>
             <Link
             to="admin"
            >
             Administrar
            </Link>
        </nav>
    </header>
</template>


