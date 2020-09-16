<template>
    <div id="app2" class="page-body">
        <div></div>
        <h3>BODY</h3>
        <h3>BODY</h3>
        <h3>BODY</h3>
        <div></div>
        <page-left></page-left>
        <page-body2></page-body2>
        <page-right></page-right>
    </div>
</template>

<script>
import PageLeft from "./components/left.vue";
import PageSecondBody from "./components/body2.vue";
import PageRight from "./components/right.vue";

export default {
    name: "page-footer",
    components: {
    PageLeft,
    PageSecondBody,
    PageRight
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