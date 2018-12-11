<template>
    <main-template>
        <h2>Index page</h2>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda at commodi culpa deleniti facilis illo
            maiores nobis numquam possimus praesentium qui, quia quod quos sint suscipit tempora velit voluptate
            voluptates.
        </p>
    </main-template>
</template>

<script>
    import MainTemplate from '~/layout/MainTemplate';

    export default {
        data() {
            return {
                title: 'Nuxt from zero'
            }
        },

        components: {
            MainTemplate
        }
    };
</script>