<template>
    <div class="d-flex px-5 py-4 flex-column">
        <div class="recommendation-title py-5">
            <h4>Complete Your Room</h4>
            <h4>With What We Designed</h4>
        </div>
        <Card :card="card" />

    </div>
</template>

<script>
import Card from './Card.vue'

export default {
    name: 'MainSlider',
    components: {
        Card
    },
    data() {
        return {
            card: [
                {
                    name: "Cangkir Mauttie",
                    price: "IDR 89.300.000",
                    img: "chair-4.png",
                },
                {
                    name: "Saman Kakka",
                    price: "IDR 14.500.000",
                    img: "chair-3.png",
                },
                {
                    name: "Lino Dino",
                    price: "IDR 22.000.000",
                    img: "chair-2.png",
                },
                {
                    name: "Syail Ammeno",
                    price: "IDR 12.000.000",
                    img: "chair-1.png",
                }
            ]
        }
    }
}
</script>

<style>

</style>