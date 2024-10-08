<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4">
                <il><NuxtLink to="/products" class="font-bold text-3xl">Nuxt</NuxtLink></il>
            </nav>
        </header>
        
        <!-- output the page content-->
         <div class="container mx-auto p-4">
            <slot />
         </div>
         <!--output the page content-->
         
         <footer class="container mx-auto p-4 flex justify-between border-t-2">
            <ul class="flex gap-4">
                <il><NuxtLink to="/">Home</NuxtLink></il>
                <il><NuxtLink to="/about">About</NuxtLink></il>
                <il><NuxtLink to="/products">Products</NuxtLink></il>
            </ul>
         </footer>
    </div>
</template>

<style scoped>
    .router-link-exact-active{
        color: #12b488;
    }
</style>