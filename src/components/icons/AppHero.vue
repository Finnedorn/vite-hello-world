<template>
    <main>
        <div class="title-wrapper">
            <h1>
                {{title}}
            </h1>
            <span>
                {{subtitle}}
            </span>
        </div>
    </main>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                title: 'il mio primo Hero!',
                subtitle: 'sottotitolone strategico'
            }
        }
    }
</script>

<style lang="scss" scoped>
.title-wrapper {
    border-radius: 20px;
    max-width: 1200px;
    height: 500px;
    background-image: url(../../../public/img/s6yztdvm5sf71.jpg);
    background-position: center;
}

h1 {
    font-size: 3rem;
    padding-top: 100px;
    text-align: center;
    color: white;
}

span {
    padding-top: 20px;
    display: block;
    text-align: center;
    color: white;
}
</style>