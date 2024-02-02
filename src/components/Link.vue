<script setup>
 
    import { RouterLink } from 'vue-router'

    defineProps({
            to:{
                type: String
            }
    })

</script>

<template>
    <RouterLink
     :to="{name: to}"
    class="rounded bg-orange-400 hover:bg-orange-800 font-bold py-2 px-5"
    >
     <slot>
     </slot>
      
    </RouterLink>
</template>


