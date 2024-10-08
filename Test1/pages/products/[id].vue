<template>
    <div>
        <h1>Pruduct details for {{ id }}</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid a consequatur fugit ducimus unde quaerat ullam, corporis accusantium culpa dignissimos cum magnam perferendis sed dolores nihil minima repudiandae vel praesentium.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params    // Diese Variable id hohlt sich den namen von /products/[id] aus der adresszeile
    
    definePageMeta({    //Das productLayout wird übernommen
        layout: 'products-layout'
    })
</script>

<style scoped>

</style>