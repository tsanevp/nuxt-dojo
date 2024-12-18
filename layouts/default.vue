<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/About">About</NuxtLink></li>
                    <li><NuxtLink to="/Products" class="btn">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <div class="container px-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style lang="css" scoped>
    .router-link-exact-active {
        color: green;
    }
</style>