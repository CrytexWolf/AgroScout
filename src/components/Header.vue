<script>
export default {};
</script>

<template>
    <header class="header">
        <div class="container">
            <div class="header__inner">
                <div class="header__inner--left">
                    <div class="header__logo">
                    <img src="../assets/LogoAgroScout.png" class="header__img">
                    </div>
                    <div class="haeder__number"><img src="../assets/iconPhone.svg" alt=""><a href="tel:+78612179118" type="phone">+7861 21791 18</a></div>
                </div>
                <div class="header__inner--right">

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
        align-items: center;
    }

    .header__inner--left {
        display: flex;
    }

    .haeder__number {
        display: flex;
        align-items: center;
        margin-left: 11px;
    }
</style>