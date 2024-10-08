<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <il><NuxtLink to="/" class="font-bold text-2xl">Nuxt</NuxtLink></il>
                <ul class="flex gap-4">
                    <il><NuxtLink to="/">Home</NuxtLink></il>
                    <il><NuxtLink to="/about">About</NuxtLink></il>
                    <il><NuxtLink to="/products" class="btn">Products</NuxtLink></il>
                </ul>
            </nav>
        </header>
        <!-- output the page content-->
         <div class="container mx-auto">
             <slot />
         </div>
         <footer class="container mx-auto p-4 flex justify-between border-t-2">
            <ul class="flex gap-4 text-neutral-600">
                <il>Impressum</il>
                <il>E-Mail: Nuxt@test.de</il>
                <il>Fax.: +49 1555 155555</il>  
                <il>Telefon: +49 1655 155555</il>
                <il>Facebook</il>
                <il>Instagram</il>
                <il>Twitter</il>
            </ul>
         </footer>
    </div>
</template>

<style scoped>
    .router-link-exact-active{
        color: #12b488;
    }
</style>