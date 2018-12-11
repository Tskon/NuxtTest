<template>
    <nav class="main-menu">
        <span>Меню: </span>
        <a href="/">Index page</a>
        <a href="/hello">Hello page</a>
    </nav>
</template>

<script>
    export default {
        name: "menu"
    }
</script>

<style scoped>
    .main-menu{
        display: flex;
        flex-direction: column;
    }
</style>