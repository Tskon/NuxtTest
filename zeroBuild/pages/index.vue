<template>
    <div id="vueApp">
        <common-header>{{ title }}</common-header>
        <main-menu></main-menu>
        <main>some text111</main>
    </div>
</template>

<script>
    import CommonHeader from '~/components/header.vue';
    import Menu from '~/components/menu.vue';

    export default {
        data() {
            return {
                title: 'Nuxt from zero'
            }
        },

        components: {
            CommonHeader,
            'main-menu': Menu
        }
    };
</script>