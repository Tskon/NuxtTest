<template>
    <header>
        <h1>Nuxt test app</h1>
        <slot name="menu"></slot>
        <p>text from slot: <slot></slot></p>
    </header>
</template>

<script>
    export default {
        name: "commonHeader"
    }
</script>

<style scoped>

</style>