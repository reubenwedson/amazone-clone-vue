<template>
    <div class="home">
        <div class="home__container">
            <img
                    class="home__image"
                    src="https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2020/May/Hero/Fuji_TallHero_45M_v2_1x._CB432458380_.jpg"
                    alt="home_banner"/>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>
    .home {
        display: flex;
        justify-content: center;
        margin: 0 auto;
        max-width: 1500px;
    }

    .home__container {
        overflow: hidden;
    }


    .home__row {
        display: flex;
        z-index: 1;
        margin: 0 5px;
    }

    .home__image {
        width: 100%;
        z-index: -1;
        margin: 0  0 -360px;
        /* mask-image: linear-gradient(to bottom, rgba(0,0,0,1), rgba(0, 0, 0, 0)); */
    }
</style>