<template>
    <Navbar :bgImgURL="bgImgURl" :title="title" :btnTitle="btnTitle" />
    <ProductContainer />
    <Footer />
</template>

<script>
import Navbar from "../components/navbar/Navbar.vue";
import ProductContainer from "../components/container/ProductContainer.vue";
import Footer from "../components/Footer.vue";
export default {
    name: "Product",
    components: {
        Navbar,
        Footer,
        ProductContainer,
    },
    data() {
        return {
            bgImgURl: new URL(
                "../assets/images/background4.jpg",
                import.meta.url
            ).href,
            title: "DANH SÁCH SẢN PHẨM",
            btnTitle: "HOME",
        };
    },
};
</script>

<style></style>
