<template>
    <div class="main-container">
        <main-header>
            <main-menu slot="menu"></main-menu>
            some text in MainTemplate for header
        </main-header>
        <main class="content">
            <nuxt/>
        </main>
        <footer class="footer">Footer of <span class="footer_highlight">test app</span></footer>
    </div>
</template>

<script>
    import MainHeader from '~/components/MainHeader';
    import MainMenu from '~/components/MainMenu';

    export default {
        name: "mainTemplate",
        components: {
            MainHeader,
            MainMenu
        }
    }
</script>

<style lang="css">
    body {
        margin: 0;
    }

    .content {
        padding: 20px 10px;
    }

    .footer {
        width: 100%;
        padding: 20px 10px;
        background-color: #000;
        color: white;
    }

    .footer_highlight {
        color: lightsalmon;
    }
</style>