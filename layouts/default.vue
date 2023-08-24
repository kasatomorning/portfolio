<template>
    <div>
        <div class="max-w-[88rem] mx-auto px-4 sm:px-6 md:px-8">
            <Navbar></Navbar>
            <slot></slot>
        </div>
    </div>
</template>
<script setup lang="ts">
useHead({
    titleTemplate: (title) => {
        return title ? `${title} - kasatomo` : 'kasatomo'
    },
});
</script>