<template>
    <div class="header">
        <img class="header-logo" src="http://pngimg.com/uploads/amazon/amazon_PNG11.png" alt="">
        <div class="header-search">
            <input class="header-searchInput" type="text"/>
            <it-icon class="header-searchIcon" name="search" />
        </div>
        <div class="header-nav">
            <div class="header-option">
                <span class="header-optionLineOne">
                    Hello Guest soufiane
                </span>
                <span class="header-optionLineTwo">
                    Sign In
                </span>
            </div>
            <div class="header-option">
                <span class="header-optionLineOne">
                    Returns
                </span>
                <span class="header-optionLineTwo">
                    & Orders
                </span>
            </div>
            <div class="header-option">
                <span class="header-optionLineOne">
                    Your
                </span>
                <span class="header-optionLineTwo">
                    Prime
                </span>
            </div>

            <div class="header-optionBasket">
                <it-icon class="header-searchIcon" name="shopping_basket" />
            </div>

        </div>
        
    </div>
</template>

<script>
export default {
    name:'Header',
}
</script>

<style>
.header {
    height: 60px;
    display: flex;
    align-items: center;
    background-color: #131921;
    position: sticky;
    top: 0;
    z-index: 100;
}

.header-logo {
    width: 100px;
    object-fit: contain;
    margin: 0 20px;
    margin-top: 18px;
}

.header-search {
    display: flex;
    flex: 1;
    align-items: center;
    border-radius: 24px;
}

.header-searchInput {
    height: 12px;
    padding: 10px;
    border: none;
    width: 100%;
}

.header-searchIcon {
    padding: 5px;
    height: 22px !important;
    background-color: #cd9042;
}

.header-optionLineOne {
    font-size: 10px;
}

.header-optionLineTwo {
    font-size: 13px;
    font-weight: 800;
}

.header-nav {
    display: flex;
    justify-content: space-evenly;
}

.header-option {
    display: flex;
    flex-direction: column;
    margin-left: 10px;
    margin-right: 10px;
    color: white;
}



</style>