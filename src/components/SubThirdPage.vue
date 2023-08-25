<template>
    <div>
        <div class="d-grid grid-1-4 align-center">
            <div class="bg-black mb-5" style="width: 20px; height: 2px"></div>
            <p style="font-size: 1.5em" class="txt-bold">{{ title }}</p>
        </div>
        <div class="d-grid grid-1-4">
            <div></div>
            <p>
                {{ desc }}
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: "SubThirdPage",
    props: {
        title: {
            type: String,
        },
        desc: {
            type: String,
        },
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
