<script></script>

<template>
    <header class="header">
        <div class="container">
            <div class="header__inner">
                <div class="header__inner--left">
                    <div class="header__logo">
                        <img src="../assets/img/LogoAgroScout.png" alt="" class="header__logo--img">
                    </div>
                    <div class="header__number">
                        <div class="header__number--icon">
                            <img src="../assets/img/svg/iconPhone.svg" alt="">
                        </div>
                        <a href="tel:+78612179118" type="phone" class="header__number--phone">+7861 21791 18</a>
                    </div>
                </div>
                <div class="header__inner--right">
                    <div class="social__items">
                        <a href="#" class="social__items--item">
                            <img src="../assets/img/svg/iconVk.svg" alt="">  
                        </a>
                        <a href="#" class="social__items--item">
                            <img src="../assets/img/svg/iconinstagram.svg" alt="">
                        </a>
                        <a href="#" class="social__items--item">
                            <img src="../assets/img/svg/iconTikTok.svg" alt="">
                        </a>
                    </div>
                    <div class="header__translate">
                        <span class="header__translate--lang">EN</span>
                        <div class="header__translate--lang">RU</div>
                    </div>
                    <div class="header__button">
                        <a class="header__button--basket" href="#"><img src="../assets/img/svg/iconBasket.svg" alt=""></a>
                        <a class="header__button--menu" href="#"><img src="../assets/img/svg/iconMenu.svg" alt=""></a>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped>

.header {
    height: 72px;
    background-color: #151515;
}

.header__inner {
    display: flex;
    justify-content: space-between;
}

.header__inner--left {
    display: flex;
    align-items: center;
}

.header__logo {
    height: 72px;
}

.header__inner--right {
    display: flex;
    align-items: center;
}

.header__number {
    display: flex;
    align-items: center;
    margin-left: 11px;
}

.header__number--phone {
    margin-left: 2px;
}

.header__translate {
    display: flex;
    margin: 0 51px 0 70px;
}

.header__translate--lang {
    margin-right: 20px;
    font-size: 24px;
}

.header__translate--lang:last-child {
    margin-right: 0;
}

.header__button--basket {
    margin-right: 22px;
}


</style>