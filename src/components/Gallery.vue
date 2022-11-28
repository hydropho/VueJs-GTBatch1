<template>
    <main class="d-flex bg-white px-5 py-5 justify-content-between">
        <!-- SIDE IMG -->
        <div class="side-img d-flex flex-column justify-content-between">
            <a href="#" class="border-rounded overflow-hidden" id="side-img">
                <img src="../assets/images/side-1.png" alt="side-1">
            </a>
            <a href="#" class="border-rounded overflow-hidden" id="side-img">
                <img src="../assets/images/side-2.png" alt="side-2">
            </a>
            <a href="#" class="border-rounded overflow-hidden" id="side-img">
                <img src="../assets/images/side-3.png" alt="side-3">
            </a>
            <a href="#" class="border-rounded overflow-hidden" id="side-img">
                <img src="../assets/images/side-1.png" alt="side-4">
            </a>
            <a href="#" class="border-rounded overflow-hidden" id="side-img">
                <img src="../assets/images/side-2.png" alt="side-5">
            </a>
        </div>

        <!-- MAIN IMG -->
        <div class="main-img mx-5">
            <img class="border-rounded" src="../assets/images/chair.png" alt="chair">
        </div>

        <!-- DESCRIPTIOM IMG -->
        <div class="desc-img">
            <h2>Chair Thatty</h2>
            <p>IDR 12.000.000</p>
            <button type="submit" class=" border-0 px-4 py-2 rounded-pill d-flex align-items-center bg-pink"><img
                    src="../assets/images/bx-cart.svg" alt="cart" class="mr-2">
                Add to
                cart</button>

            <hr>

            <p>
                Tailored to a level perfection synonymous with that of a Savile Row suit adn with understated quality in
                the detail,
                Jetty has been influenced by timless 1950s style.
            </p>
            <p>
                Providing a subtle nod to the past, Jetty also provides a perfect solution for the way we work today. A
                comprehensive
                product family, Jetty features a variety of elegant chairs and sofas.
            </p>
        </div>
    </main>
</template>

<script>
export default {
    name: 'MainGallery'
}
</script>

<style>

</style>