<template>
    <div id="app2" class="page-body">
        <div></div>
        <h3>BODY</h3>
        <h3>BODY</h3>
        <h3>BODY</h3>
        <div></div>
        <page-body2></page-body2>
    </div>
</template>

<script>

export default {
    name: "app2",
    components: {
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