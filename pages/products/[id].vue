<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dignissimos, nulla illum placeat corporis nam aperiam eius quia nemo soluta quod.</p>
    </div>
</template>

<script setup>
    const {id} = useRoute().params;

    definePageMeta({
        layout: 'products',
    });
</script>

<style lang="scss" scoped>

</style>