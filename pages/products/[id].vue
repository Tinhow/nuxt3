<template>
    <div>
        <h1>Products details for {{ id }}</h1>
    </div>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Labore enim atque perspiciatis doloribus hic quis vel quod ipsam, 
        quae repellatelit maxime autem assumenda quaerat exercitationem 
        accusantium inventore blanditiis fugit! 
    </p>
</template>

<script setup>
    const { id } = useRoute().params 

</script>

<style scoped>

</style>