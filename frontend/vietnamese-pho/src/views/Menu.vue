<template>
    <Navbar :title="title" :bgImgURL="bgImgURl" :btnTitle="btnTitle" />
    <MenuContainer />
    <Footer />
</template>

<script>
import Navbar from "../components/navbar/Navbar.vue";
import MenuContainer from "../components/container/MenuContainer.vue";
import Footer from "../components/Footer.vue";

export default {
    name: "Menu",
    components: {
        Navbar,
        Footer,
        MenuContainer,
    },
    data() {
        return {
            title: "Menu",
            bgImgURl: new URL(
                "../assets/images/background4.jpg",
                import.meta.url
            ).href,
            btnTitle: "HOME",
        };
    },
};
</script>

<style></style>
