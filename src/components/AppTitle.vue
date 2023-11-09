<template>
    <main>
        <h1>
            {{title}}
        </h1>
    </main>
</template>

<script>
    export default {
        name: 'AppTitle',
        data() {
            return {
                title: 'la mia prima app con Vite!'
            }
        }
    }
</script>

<style lang="scss" scoped>
    h1 {
        padding-top: 20px;
        text-align: center;
        color: red;
    }
</style>