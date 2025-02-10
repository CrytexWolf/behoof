<template>
    <header class="header">
        <div class="container">
            <div class="header__inner">
                <section class="header__logo">
                    <div class="logo__img">
                        <img class="logo" src="/logo.png" alt="">
                    </div>
                    <span class="logo__text">Лучшие цены<br/>в интернет-магазинах</span>
                </section>
                <section class="header__search--nav">
                    <div class="header__search">
                        <div class="header__selected">
                            <span class="header__selected--text">Каталог товаров</span>
                            <div class="header__selected--img"><img src="/Vector.svg" alt=""></div>
                        </div>
                        <form class="header__input">
                            <input class="header__input--search" type="text" placeholder="Поиск товаров">
                            <div class="header__input--img"><img class="input--img" src="/Search-normal.svg" alt=""></div>
                        </form>
                    </div>
                    <div class="header__links">
                        <a class="links" href=""><img src="/heart.svg" alt=""></a>
                        <a class="links" href=""><img src="/chart.svg" alt=""></a>
                        <a class="links" href=""><img src="/frame.svg" alt=""></a>
                    </div>
                </section>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    
}
</script>

<style>
    .header {
        width: 100%;
        height: 76px;
    }

    .header__inner {
        display: flex;
        justify-content: space-between;
    }

    .header__logo {
        display: flex;
        justify-content: space-between;
    }

    .logo__img {}

    .logo__text {
        font-family: var(--font-family);
        font-size: 14px;
        line-height: 129%;
        color: #263141;
    }

    .header__search--nav {
        display: flex;
        justify-content: space-between;
    }

    .header__search {
        display: flex;
        justify-content: center;
    }

    .header__selected {
        position: relative;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 16px 20px;
        width: 200px;
        height: 52px;
        background: #ff4d4d;
        border-radius: 8px 0 0 8px;

        font-family: var(--font-family);
        font-weight: 500;
        font-size: 16px;
        line-height: 125%;
        color: #fff;
    }

    .header__selected--img {
        position: absolute;
        right: 25px;
        top: 14px;
        }


    .header__input {
        position: relative;
    }

    .header__input--search {
        border-radius: 0 8px 8px 0;
        width: 841px;
        height: 52px;
        background: #f2f5f9;
        border: none;
    }

    .header__input--img {
        position: absolute;
        left: 0;
        top: 0;
    }

    .input--img {
    }

    .header__links {
        display: flex;
    }

    .links {
        border-radius: 8px;
        padding: 14px;
        width: 52px;
        height: 52px;
        background: #f2f5f9;
    }
</style>