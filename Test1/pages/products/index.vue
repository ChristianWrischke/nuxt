<template>
    
    <div>
        <h2>Products</h2>
        <div class="grid grid-cols-3 gap-4">

            <div class="col-start-1">
                <h3 class="p-4">Product 1</h3>
                <img class="hover:scale-105" src="C:\Users\wrisc\dev\nuxt\Test1\images\Bild1.jpg">
            </div>

            <div class="col-start-2">
                <h3 class="p-4">Product 2</h3>
                <img class="hover:scale-105" src="C:\Users\wrisc\dev\nuxt\Test1\images\Bild2.jpg">
            </div>

            <div class="col-start-3">
                <h3 class="p-4">Product 3</h3>
                <img class="hover:scale-105" src="C:\Users\wrisc\dev\nuxt\Test1\images\Bild3.jpg">
            </div>
        </div>
    </div>
    
</template>

<script setup>
    definePageMeta({
        layout: 'products-layout'
    })
</script>

<style scoped>

</style>