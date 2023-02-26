<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quidem qui explicabo ipsa, 
            veniam id asperiores illo dolores ratione tempore, dolor, 
            ab neque totam cupiditate voluptatum laborum dicta nihil? Voluptatem, mollitia.
        </p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quidem qui explicabo ipsa, 
            veniam id asperiores illo dolores ratione tempore, dolor, 
            ab neque totam cupiditate voluptatum laborum dicta nihil? Voluptatem, mollitia.
        </p>
        <div>Data: {{ data }}</div>
    </div>
</template>

<script setup>
    // const {data} = await useFetch('/api/ninja?name=mario', {
    //         method: 'post',
    //         body: {
    //             age: 30,
    //     }
    // });
    const {data} = await useFetch('/api/currency/GBP');
</script>

<style scoped>
    h2{
        margin-bottom: 20px;
        font-size: 36px;
    }
    p{
        margin: 20px 0;
    }
</style>