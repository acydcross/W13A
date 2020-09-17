<template>
    <div id="app4" class="page-third-body">
        <div></div>
        <h3>BODY3</h3>
        <h3>BODY3</h3>
        <h3>BODY3</h3>
        <div></div>
    </div>
</template>

<script>

export default {
    name: "app4",
    components: {
  }
}
</script>

<style scoped>
    .page-third-body {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
    }
</style>