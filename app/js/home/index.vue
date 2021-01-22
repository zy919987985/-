<template lang="html">
    <div>
        <Heador/>
        <Hswiper/>
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
import Hswiper from "../home/hswiper.vue"
import Novice from "../home/novice.vue"
import Borrow from "../home/borrow.vue"
import Money from "../home/money.vue"
import Product from "../home/product.vue"
import Life from "../home/life.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
export default {
    components: {
        Heador,
        Hswiper,
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
