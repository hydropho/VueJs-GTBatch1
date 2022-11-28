<template>
    <footer class="d-flex flex-column bg-white px-5">
        <!-- LOGO -->
        <div class="d-flex justify-content-center py-5">
            <img src="../assets/images/logo.png" alt="logo">
        </div>

        <!-- LIST -->
        <div class="links d-flex flex-row justify-content-around pb-5">
            <div class="list-1 d-flex flex-column">
                <a href="#" class="text-dark nav-link"><b>Overview</b></a>
                <a href="#" class="text-dark nav-link">Shipping</a>
                <a href="#" class="text-dark nav-link">Refund</a>
                <a href="#" class="text-dark nav-link">Promotion</a>
            </div>
            <div class="list-2 d-flex flex-column">
                <a href="#" class="text-dark nav-link"><b>Company</b></a>
                <a href="#" class="text-dark nav-link">About</a>
                <a href="#" class="text-dark nav-link">Career</a>
                <a href="#" class="text-dark nav-link">Contact Us</a>
            </div>
            <div class="list-3 d-flex flex-column">
                <a href="#" class="text-dark nav-link"><b>Explore</b></a>
                <a href="#" class="text-dark nav-link">Terms & Conds</a>
                <a href="#" class="text-dark nav-link">Privacy Policy</a>
                <a href="#" class="text-dark nav-link">For Developer</a>
            </div>
            <form action="POST" id="emailForm">
                <p><b>Special Letter</b></p>
                <div class="send-email bg-light">
                    <input class="input-email bg-light" type="email" name="email" id="email"
                        placeholder="Your email address" required>
                    <button type="submit" class="btn-submit"><img src="../assets/images/tele-icon.png" alt="send"
                            class="p-2"></button>
                </div>
            </form>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'MainFooter'
}
</script>

<style>

</style>