<template>
    <div id="vueApp">
        <common-header>Текст хедера</common-header>
        <h1>{{ title }}</h1>
        <main>some text111</main>
    </div>
</template>

<script>
    import CommonHeader from '~/components/header.vue';

    export default {
        data() {
            return {
                title: 'Nuxt from zero'
            }
        },

        components: {
            CommonHeader
        }
    };
</script>