<template>
    <div class="txt-left ps-5 pe-5">
        <div class="bg-white ps-6 pt-6 pe-6 pb-6">
            <h1 style="line-height: normal" class="mb-5 txt-blue">
                OUR SPECIALITY
            </h1>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis
                euismod libero vel leo auctor, in venenatis nulla consequat. Sed
                commodo nunc sit amet congue aliquam.
            </p>
            <div class="pt-5">
                <v-carousel
                    hide-delimiters
                    :show-arrows="false"
                    v-model="model"
                    style="height: 200px">
                    <v-carousel-item class="txt-center">
                        <img
                            alt="Vue logo"
                            src="../assets/img/Group (1).png"
                            style="width: 50%" />
                    </v-carousel-item>
                    <v-carousel-item class="txt-center">
                        <img
                            alt="Vue logo"
                            src="../assets/img/Group (2).png"
                            style="width: 50%" />
                    </v-carousel-item>
                    <v-carousel-item class="txt-center">
                        <img
                            alt="Vue logo"
                            src="../assets/img/Group.png"
                            style="width: 50%" />
                    </v-carousel-item>
                </v-carousel>
                <div class="pt-10">
                    <p class="text-center">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Duis euismod libero vel leo auctor, in venenatis nulla
                        consequat. Sed commodo nunc sit amet congue aliquam.
                    </p>
                </div>
                <div class="d-flex" justify="space-around">
                    <v-icon @click="model--" class="mt-15 pt-2 pe-2 pb-2 ps-2"
                        >mdi-arrow-left</v-icon
                    >
                    <v-carousel
                        v-model="model"
                        style="height: 100px; color: black"
                        :show-arrows="false"
                        hide-delimiter-background>
                        <v-carousel-item></v-carousel-item>
                        <v-carousel-item></v-carousel-item>
                        <v-carousel-item></v-carousel-item>
                    </v-carousel>
                    <v-icon
                        color="#1ba0e1"
                        @click="model++"
                        class="mt-15 pt-2 pe-2 pb-2 ps-2"
                        >mdi-arrow-right</v-icon
                    >
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FourthPage",
    data() {
        return {
            img: [
                "../assets/img/Group (1).png",
                "../assets/img/Group (2).png",
                "../assets/img/Group.png",
            ],
            model: 0,
        };
    },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
    margin: 40px 0 0;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}
</style>
