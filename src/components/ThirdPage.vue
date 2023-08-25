<template>
    <div class="txt-left ps-10 pe-10">
        <div class="txt-center">
            <h1 style="line-height: normal" class="mb-5 txt-blue">
                Our Core Values
            </h1>
        </div>
        <p>
            Ridiculus laoreet libero pretium et, sit vel elementum convallis
            fames. Sit suspendisse etiam eget egestas. Aliquet odio et lectus
            etiam sit.
        </p>
        <p>
            In mauris rutrum ac ut volutpat, ornare nibh diam. Montes, vitae,
            nec amet enim.
        </p>
        <SubThirdPage
            title="Dedication"
            desc="Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat." />
        <SubThirdPage
            title="Intellectual Honesty"
            desc="Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias conse." />
        <SubThirdPage
            title="Curiosity"
            desc="At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque." />
        <img
            alt="Vue logo"
            src="../assets/img/Core Values Illustration.png"
            style="width: 100%"
            class="mt-5" />
    </div>
</template>

<script>
import SubThirdPage from "./SubThirdPage.vue";

export default {
    name: "ThirdPage",
    components: { SubThirdPage },
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
