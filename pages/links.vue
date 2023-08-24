<template>
    <div class="lg:pl-[19.5rem]">
        <div class="max-w-3xl mx-auto pt-10 xl:max-w-none xl:ml-0 xl:pr-16">
            <div class="mx-auto max-w-sm my-[1rem] text-center">
                <h1
                    class="inline-block text-5xl sm:text-5xl font-extrabold text-slate-900 tracking-tight dark:text-slate-200">
                    Links</h1>
            </div>
            <a href="https://github.com/kasatomorning?tab=repositories" class="flex items-center mb-4">
                <img src="~/assets/image/GitHub-Mark.png" class="h-10 w-10">
                <h2 class="inline-block text-4xl relative border-none  m-2">GitHub</h2>
            </a>
            <a href="https://twitter.com/fortsukucollege" class="flex items-center mb-4">
                <img src="~/assets/image/Twitter-Logo.png" class="w-10">
                <h2 class="inline-block text-4xl relative border-none  m-2">Twitter</h2>
            </a>
        </div>
    </div>
</template>
<script setup lang="ts">
useHead({
    title:'Links'
})
</script>