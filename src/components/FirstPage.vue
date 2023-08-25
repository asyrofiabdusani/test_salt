<template>
    <div>
        <img alt="Vue logo" src="../assets/img/Hero Image.png" />
        <div class="relative translate-y-banner" style="height: 265px">
            <div class="absolute">
                <img alt="Vue logo" src="../assets/img/Vector 42.png" />
            </div>
            <div class="absolute">
                <img alt="Vue logo" src="../assets/img/Rectangle 121.png" />
            </div>
            <div
                class="absolute txt-left ms-10 me-10 d-flex flex-column just-center txt-white"
                style="height: 380px">
                <h1 style="line-height: normal">{{ msg }}</h1>
                <p class="mt-5">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Officia debitis deserunt quibusdam temporibus neque totam
                    consectetur.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FirstPage",
    props: {
        msg: String,
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
