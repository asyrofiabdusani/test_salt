<template>
    <v-app class="main-container">
        <v-main>
            <nav class="d-flex just-s-between mt-5 me-10 mb-5 ms-10">
                <img alt="Vue logo" src="./assets/img/Group 215.png" />
                <v-icon color="black">mdi-menu</v-icon>
            </nav>
            <router-view />
        </v-main>
    </v-app>
</template>

<style>
@import "@/assets/style/style.css";
@import "@/assets/style/main.css";

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
