<template>
    <header class="header">
        <nav class="nav">
            <div class="header__nav containerHeader">
                <div class="nav__logo">
                    <div class="logo__img">
                        <div class="logo__img__eyes">
                            <img src="../assets/images/Vector(Stroke).svg" alt="">
                            <img src="../assets/images/Vector(Stroke).svg" alt="">
                        </div>
                        <img class="atom" src="../assets/images/atom.svg" alt="">
                    </div>
                    <h1 class="nav__logo">
                        TSX
                    </h1>
                </div>
                <div class="nav__content">
                    <div class="nav__links">
                        <ul>
                            <a class="link__list" href="!#">
                                <img src="../assets/images/icon-heart.svg" alt="">
                                <span>Избранное</span>
                            </a>
                        </ul>
                        <ul>
                            <a class="link__list" href="!#">
                                <img src="../assets/images/icon-package.svg" alt="">
                                <span>Заказы</span>
                            </a>
                        </ul>
                        <ul>
                            <a class="link__list" href="!#">
                                <img src="../assets/images/icon-basket.svg" alt="">
                                <span>Корзина</span>
                            </a>
                        </ul>
                    </div>
                    <div class="nav__user">
                        <img src="../assets/images/avatar.png" alt="">
                        <span>Алексей</span>
                        <button>
                            <img src="../assets/images/chevron-down.svg" alt="">
                        </button>
                    </div>
                    <div class="nav__btn">
                        <button>
                            Подать объявления
                        </button>
                        <button>
                            <img src="../assets/images/ru.png" alt="">
                        </button>
                    </div>
                </div>
            </div>
        </nav>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
header {
    background: white;
}

nav {
    padding: 11px 0;
    background: rgba(85, 183, 183, 0.69);
}

.header__nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav__logo {
    display: flex;
    align-items: center;
    gap: 20px;
}

.logo__img {
    margin-bottom: -26px;
    display: flex;
    flex-direction: column;
    gap: 12.75px;
}

.logo__img__eyes {
    display: flex;
    gap: 6.85px;
}

.nav__logo {
    color: var(--blackColor);
    text-align: center;
    font-family: Road Rage;
    font-size: 50px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
}

.nav__content {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav__links {
    display: flex;
    align-items: center;
    gap: 24px;
}

.link__list {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 8px;
}

.link__list img {
    width: 24px;
    height: 24px;
    position: relative;
}

.link__list span {
    color: #414141;
    text-align: center;
    font-family: Rubik;
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
}

.nav__user {
    padding: 8px;
    margin-left: 24px;
    display: flex;
    align-items: center;
    gap: 10px;
}

.nav__user span {
    color: #232323;
    font-family: Rubik;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
}

.nav__user button {
    display: flex;
    align-items: center;
    margin-left: 24px;
}

.nav__btn {
    display: flex;
    align-items: center;
    gap: 34px;
    margin-left: 24px;
}

.nav__btn button:nth-child(1) {
    border-radius: 5px;
    padding: 11px 14px;
    background: #0C7F8E;
    color: #FFF;
    font-family: Inter;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;

    &:focus {
        outline: 3px solid white;
    }
}

@media(max-width: 994.99px) {
    .header__nav {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 30px;
    }
}

@media(max-width: 719.99px) {
    .nav__links {
        gap: 13px;
    }
    .nav__user {
        margin-left: 16px;
    }
    .nav__btn {
        margin-left: 8px;
        gap: 10px;
    }
    .nav__user button {
        margin-left: 14px;
    }
    .nav__btn button:nth-child(1) {
        font-size: 15px;
    }
}

@media(max-width: 588.99px) {
    .nav__content {
        justify-content: center;
        flex-wrap: wrap;
        row-gap: 30px;
    }
}
</style>