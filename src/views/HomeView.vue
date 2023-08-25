<template>
    <div class="main-container">
        <FirstPage msg="Discover Your Wonder" />
        <v-icon
            large
            color="black"
            class="translate-y-chevron bg-white pt-2 pe-2 pb-2 ps-2"
            style="border-radius: 100%"
            >mdi-chevron-double-down</v-icon
        >
        <SecondPage class="pt-16 pb-16" />
        <ThirdPage class="pt-16 pb-16 bg-gray" />
        <FourthPage class="pt-16 pb-16 bg-blue" />
        <FivethPage class="pt-16 pb-16 bg-footer" />
    </div>
</template>

<script>
// @ is an alias to /src
import FirstPage from "@/components/FirstPage.vue";
import SecondPage from "@/components/SecondPage.vue";
import ThirdPage from "@/components/ThirdPage.vue";
import FourthPage from "@/components/FourthPage.vue";
import FivethPage from "@/components/FivethPage.vue";

export default {
    name: "HomeView",
    components: {
        FirstPage,
        SecondPage,
        ThirdPage,
        FourthPage,
        FivethPage,
    },
};
</script>

<style>
@import "@/assets/style/main.css";
</style>
