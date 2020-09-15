<template>
    <div class="header">
        <img
                class="header__logo"
                src="http://pngimg.com/uploads/amazon/amazon_PNG11.png"
                alt="header__logo"
        />
        <div class="header__search">
            <input class="header__searchInput" type="text" />
            <font-awesome-icon class="header__searchIcon" icon="search" />
        </div>
        <div class="header__nav">
            <div class="header__option">
                <span class="header__optionLineOne">Hello Guest</span>
                <span class="header__optionLineTwo">Sign In</span>
            </div>
            <div class="header__option">
                <span class="header__optionLineOne">Returns</span>
                <span class="header__optionLineTwo">& Orders</span>
            </div>
            <div class="header__option">
                <span class="header__optionLineOne">Your</span>
                <span class="header__optionLineTwo">Prime</span>
            </div>
            <div class="header__optionBasket">
                <font-awesome-icon icon="shopping-cart" />
                <span class="header__optionLineTwo header__basketCount">0</span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    .header {
        height: 60px;
        display: flex;
        align-items: center;
        background-color: #131921;
        position: sticky;
        top: 0;
        z-index: 100;
    }

    .header__logo {
        width: 100px;
        object-fit: contain;
        margin: 18px 20px 0;
    }

    .header__search {
        display: flex;
        flex: 1;
        align-items: center;
        border-radius: 24px;
    }

    .header__searchInput {
        height: 12px;
        padding: 10px;
        border: none;
        width: 100%;
    }

    .header__searchIcon {
        padding: 5px;
        height: 22px !important;
        background-color: #cd9042;

    }

    .header__nav {
        display: flex;
        justify-content: space-evenly;
    }

    .header__option {
        display: flex;
        flex-direction: column;
        margin: 0 10px;
        color: #ffffff;
    }

    .header__optionLineOne {
        font-size: 10px;
    }

    .header__optionLineTwo {
        font-size: 13px;
        font-weight: 800;
    }

    .header__optionBasket {
        display: flex;
        align-items: center;
        color: #ffffff;
    }

    .header__basketCount {
        margin: 0 10px;
    }
</style>