<template>
    <div class="txt-left ps-5 pe-5">
        <img
            alt="Vue logo"
            class="mb-5"
            src="../assets/img/Group 215 white.png" />
        <div class="bg-white ps-6 pt-6 pe-6 pb-6">
            <v-select
                :items="items"
                label="TECHNOLOGY DEPARTMENT"
                outlined
                color="#1ba0e1"></v-select>
            <div style="width: 60%">
                <p>
                    Jl. Lembong No 8 Kel. Braga Kec. Sumur Bandung, Kota
                    Bandung, Jawa Barat
                </p>
            </div>
        </div>
        <div class="d-flex flex-column gap-1 pt-10">
            <p class="txt-white">Who We Are</p>
            <p class="txt-white">Our Values</p>
            <p class="txt-white">The Perks</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "FivethPage",
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
