<template>
    <footer class="footer">
        <div class="container foter__content">
            <div class="footer__content">
                <ul class="footer__content__list">
                    <li><a class="footer__content__list__links" href="!#">Мобильное приложения</a></li>
                    <li><a class="footer__content__list__links" href="!#">Помощь</a></li>
                    <li><a class="footer__content__list__links" href="!#">Платные услуги</a></li>
                    <li><a class="footer__content__list__links" href="!#">Бизнес на ТSХ</a></li>
                    <li><a class="footer__content__list__links" href="!#">Реклама на сайте</a></li>
                </ul>
                <ul class="footer__content__list">
                    <li><a class="footer__content__list__links" href="!#">Как продавать и покупать?</a></li>
                    <li><a class="footer__content__list__links" href="!#">Правила безопасности</a></li>
                    <li><a class="footer__content__list__links" href="!#">Карта сайта</a></li>
                    <li><a class="footer__content__list__links" href="!#">Карта регионов</a></li>
                    <li><a class="footer__content__list__links" href="!#">Обратная связь</a></li>
                </ul>
                <img src="../assets/images/apps.png" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss">
footer {
    padding-top: 16px;
    padding-bottom: 34px;
    background: rgba(152, 218, 218, 0.69);
}

.footer__content {
    display: flex;
    align-items: center;
    justify-content: space-between;

    &__list {
        display: flex;
        flex-direction: column;
        gap: 25px;

        &__links {
            color: #000;
            font-family: Rubik;
            font-size: 16px;
            font-style: normal;
            font-weight: 400;
            line-height: 150%;
        }
    }
}

@media (max-width: 994.99px) {
    .footer__content {
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        gap: 40px;
    }
}</style>