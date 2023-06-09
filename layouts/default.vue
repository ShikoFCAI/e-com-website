<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold text-xl">E-commerce Clothing Website</NuxtLink>
                <ul class="flex gap-4">
                    <li>
                        <NuxtLink to="/" class="font-medium"> Home </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about" class="font-medium"> About </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/products" class="btn font-medium"> Products </NuxtLink>
                        
                    </li>
                </ul>
            </nav>
        </header>
        <div class="flex items-center gap-2 absolute right-10 pt-4">
            <p class="font-medium italic"> Our products are here </p>
            <img src="../assets/img/arrow.png" class=" w-8 ">
        </div>
    </div>

    <div class="container mx-auto p-4">
        <slot />
    </div>
</template>

<style>
.router-link-exact-active{
    color: green;
}
</style>