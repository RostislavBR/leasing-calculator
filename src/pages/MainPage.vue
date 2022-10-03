<template>
    <main class="main">
        <div class="container">
            <MainTitle/>
        </div>
    </main>
</template>

<script>
    import MainTitle from "@/components/main/MainTitle";

    export default {
        name: "MainPage",
        components: {MainTitle}
    }
</script>

<style lang="scss">
    .main {
        height: 100%;
        .container {
            width: 1440px;
            margin: 0 auto;
        }
    }
</style>