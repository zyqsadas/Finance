<template lang="html">
    <div>
        <Heador/>
        <Hlider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
        <Life/>
        <Footer/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Hlider from "./hslider.vue"
import Novice from "./novice.vue"
import Borrow from "./borrow.vue"
import Money from "./money.vue"
import Product from "./product.vue"
import Life from "./life.vue"
export default {
    components: {
        Heador,
        Hlider,
        Novice,
        Borrow,
        Money,
        Product,
        Life,
        Footer,
        Navbar,
    },
}
</script>


