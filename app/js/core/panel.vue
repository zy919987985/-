<template>
    <setion :class="[panelClass,cname]">
        <h4>--{{ title }}--</h4>
        <slot/>
    </setion>
</template>

<script>

export default {
    props: {
        cname: {
            type: String,
            default: "",
        },
        title: {
            type: String,
            default: "",
        },
    },
    data() {
        return {
            panelClass: "panel",
        }
    },
    methods: {},
}

</script>
<style lang='scss' scoped>
@import "../../css/elemnt.scss";
.panel{
    @include panel;
}
</style>
