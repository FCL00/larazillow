<template>
    <div>
        <h1>Index</h1>
    </div>
    <Link href="/show">Show Page</Link>
    <div>
        {{ message }}
    </div>
   
</template>


<script setup>
    import { Link } from '@inertiajs/vue3';
   
    defineProps({ message : String });
</script>

