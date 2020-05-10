<template>
    <div class="loading">
        <img class="loading-img" src="https://sun1-89.userapi.com/h3oN2Zhp1yPG_tsiBOD1Um98eXcFm2nvV2A-LA/fKGr82_LyGU.jpg">
        Подождите идёт загрузка..
    </div>
</template>

<style lang="scss" scoped>
    .loading {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 100px;
    }

    @keyframes rotating {
        from {
            transform: rotate(0deg);
        }
        to {
            transform: rotate(360deg);
        }
    }

    .loading-img {
        width: 300px;
        height: 300px;
        animation: rotating 5s linear infinite;
        margin-bottom: 100px;
    }
</style>

<script>
    export default {

    }
</script>