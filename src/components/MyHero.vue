<template>
  <div>
    <div>
        <div class="my_jumbotron">
            <img :src="img"  :alt="img_alt">

            <div class="text">
                <h2>{{ title }}</h2>

                <p>{{ paragraph }}</p>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: 'MyHero',
        props: {
            img: String,
            img_alt: String,
            title: String,
            paragraph: String
        }
    }
</script>

<style scoped lang="scss">
    img {
        width: 70rem;
    }

    .my_jumbotron {
        position: relative;
        width: fit-content;
        margin: 0 auto;
    }

    .text {
        text-align: left;
        color: white;
    }

    .text h2 {
        position: absolute;
        font-size: 3rem;
        top: 2rem;
        left: 3rem;
    }

    .text p {
        position: absolute;
        font-size: 18px;
        bottom: 2rem;
        left: 3rem;
    }
</style>