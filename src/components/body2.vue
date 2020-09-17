<template>
    <div id="app3" class="page-body2">
        <div></div>
        <h3>BODY2</h3>
        <h3>BODY2</h3>
        <h3>BODY2</h3>
        <div></div>
    </div>
</template>

<script>

export default {
    name: "app3",
    components: {
  }
}
</script>

<style scoped>
    .page-body2 {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
    }
</style>