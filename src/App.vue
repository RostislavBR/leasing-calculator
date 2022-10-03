<template>
    <div id="app">
        <router-view/>
    </div>
</template>

<script>

</script>

<style lang="scss">
    * {
        margin: 0;
        padding: 0;
        font-family: $Nekst;
    }

    body, html {
        width: 100%;
        height: 100%;
        overflow: hidden;
        background: $white;
    }

    #app {
        height: 100%;
    }
</style>
