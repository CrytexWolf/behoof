<template>
    <header class="header">
        <div class="container">
            <div class="header__inner">
                <section class="header__logo">
                    <div class="logo__img">
                        <img class="logo" src="/logo.png" alt="">
                    </div>
                    <div class="logo__text">Лучшие цены<br/>в интернет-магазинах</div>
                </section>
                <section class="header__search--nav">
                    <div class="header__search">
                        <div class="header__selected">
                            <span class="header__selected--text">Каталог товаров</span>
                            <div class="header__selected--img"><img src="/Vector.svg" alt=""></div>
                        </div>
                        <section class="header__input">
                            <input class="header__input--search" type="search" placeholder="Поиск товаров">
                            <div class="header__input--img"><img class="input--img" src="/Search-normal.svg" alt=""></div>
                        </section>
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
        border-bottom: 1px solid #dddddd;
        background-color: #FDFDFD;
    }

    .header__inner {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 12px 0;
    }

    .header__logo {
        display: flex;
        gap: 12px;
        height: 52px;
        align-items: center;
    }

    .logo__text {
        font-family: var(--font-family);
        font-size: 1rem;
        line-height: 129%;
        color: #263141;
        min-width: 164px;
    }

    .header__search--nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        gap: 15px;
    }

    .header__search {
        display: flex;
        justify-content: center;
        width: 100%;
    }

    .header__selected {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        height: 52px;
        min-width: 200px;
        background: #ff4d4d;
        border-radius: 8px 0 0 8px;

        font-family: var(--font-family);
        font-weight: 500;
        font-size: 1rem;
        line-height: 125%;
        color: #fff;
    }

    .header__selected--text {
        font-size: 1.06rem;
    }

    .header__selected--img {
        }


    .header__input {
        position: relative;
        flex-grow: 1;
    }

    .header__input--search {
        border-radius: 0 8px 8px 0;
        width: 100%;
        padding: 10px 10px 10px 45px;
        height: 52px;
        background: #f2f5f9;
        border: none;
    }

    .header__input--img {
        position: absolute;
        left: 10px;
        top: 50%;
        transform: translateY(-50%);
    }

    .input--img {
    }

    .header__links {
        display: flex;
        gap: 15px;
    }

    .links {
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 8px;
        width: 52px;
        height: 52px;
        background: #f2f5f9;
    }

    @media (max-width: 375px) {
        .header {
            height: 116px;
        }

        .header__inner {
            flex-wrap: wrap;
            padding: 8px 0;
        }

        .header__input--search {
            border-radius: 8px;
        }

        .header__selected {
            display: none;
        }

        .header__links {
            display: none;
        }
    }
</style>