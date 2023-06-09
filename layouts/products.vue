<template>
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4">
            <NuxtLink to="/" class="font-bold">Back home</NuxtLink>
        </nav>

        <div class="container mx-auto p-4">
            <slot />
        </div>

    </header>
    <footer class="container mx-auto p-4 flex justify-between border-t-2">
        <ul class="flex gap-4">
            <li>
                <NuxtLink to="/" class="font-medium"> Home </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about" class="font-medium"> About </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/products" class="font-medium"> Products </NuxtLink>
            </li>
        </ul>
    </footer>
</template>