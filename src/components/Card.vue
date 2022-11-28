<template>
    <div class="recommendation-card d-flex flex-row justify-content-between">
        <div class="card1 bg-white px-3 py-4 border-rounded" v-for="card in card" :key="card">
            <img :src="require('@/assets/images/' + card.img)" alt="chair-4"
                class="border-rounded overflow-hidden mb-3">
            <h6>{{ card.name }}</h6>
            <p>{{ card.price }}</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SliderCard',
    props: ["card"]
}
</script>

<style>

</style>