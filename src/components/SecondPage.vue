<template>
    <div class="txt-left ms-10 me-10">
        <h1 style="line-height: normal" class="txt-blue">{{ title[idx] }}</h1>
        <h4 class="mt-5 mb-3">{{ subTitle[idx] }}</h4>
        <p>
            {{ desc[idx] }}
        </p>
        <div class="d-flex just-s-between align-center mt-15 mb-5">
            <div class="d-flex gap-0p5">
                <h2>0{{ idx + 1 }}</h2>
                <h2 class="txt-gray">/</h2>
                <h4 class="mt-2 txt-gray">0{{ title.length }}</h4>
            </div>
            <div>
                <v-icon
                    color="#c0c0c0"
                    class="bg-gray pt-2 pe-4 pb-2 ps-4"
                    @click="dec"
                    >mdi-arrow-left</v-icon
                >
                <v-icon
                    color="white"
                    class="bg-blue pt-2 pe-4 pb-2 ps-4"
                    @click="inc"
                    >mdi-arrow-right</v-icon
                >
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "SecondPage",
    data() {
        return {
            idx: 0,
            title: ["Who we are", "What we do", "How we do"],
            subTitle: [
                "Technology Company",
                "Professional Brand Management",
                "Strategize, Design, Collaborate",
            ],
            desc: [
                "Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.",
                "Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.",
                "Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse sequam nihil molestiae consequatur.",
            ],
        };
    },
    methods: {
        inc() {
            if (this.idx < this.title.length - 1) {
                this.idx++;
            }
        },
        dec() {
            if (this.idx > 0) {
                this.idx--;
            }
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
