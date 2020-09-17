<template>
    <div id="app2" class="page-body">
        <div></div>
        <h3>BODY</h3>
        <h3>BODY</h3>
        <h3>BODY</h3>
        <div></div>
        <page-second-body></page-second-body>
        <page-third-body></page-third-body>
        <page-fourth-body></page-fourth-body>
    </div>
</template>

<script>
import PageSecondBody from "../components/subcomponents/body2.vue";
import PageThirdBody from "../components/subcomponents/body3.vue";
import PageFourthBody from "../components/subcomponents/body4.vue";

export default {
    name: "app2",
    components: {
        PageSecondBody,
        PageThirdBody,
        PageFourthBody
  }
}
</script>

<style scoped>
    .page-body {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
    }
</style>