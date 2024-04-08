<header class="header">
    <div class="container">
        <div class="header__wrap">
            <div class="header__logo">
                <img src="./img/for logo/1.png" alt="logo">
            </div>
            <!-- отдел навигации -->
            <nav class="header__nav">
                <ul class="header__list">
                    <li>
                        <button on:click={goHome} class="header__link">
                            Главная
                        </button>
                    </li>
                    <li>
                        <a href="/location" class="header__link">
                            Локации
                        </a>
                    </li>
                    <li>
                        <a href="/action" class="header__link">
                            Акции
                        </a>
                    </li>
                    <li>
                        <a href="/feedback" class="header__link">
                            Отзывы
                        </a>
                    </li> 
                </ul>
            </nav>
            <!-- иконки навигации -->
            <div class="header__icons">
                <ul class="header__icons-list">
                    <li class="header__icon">
                        <img src="../img/icons/search.svg" alt="icon">
                    </li>
                    <li class="header__icon">
                        <img src="./img/icons/bag.svg" alt="icon">
                    </li>
                    <li class="header__icon">
                        <img src="./img/icons/bag.svg" alt="icon">
                    </li>
                </ul>
            </div>

        </div>
    </div>
</header>
   <!-- секция акций -->
   <section id="action" class="best">
    <div class="container">
        <div class="best__head">
            <h2 id="location" class="title best__title">
                Акции
            </h2>
            <a href="#" class="best__link"></a>
        </div>
<!-- секция главная -->
             <!-- отдел акций -->
             <div class="best__row">
                <!-- акция первая -->
            <div class="best__column">
                <div class="best__card">
                    <div class="best__pic">
                        <img src="./img/location/9.jpg" alt="111">
                        <div class="best__texts">
                            <h4 class="best__name">
                                Царство земли
                            </h4>
                            <p class="best__price">
                                <s>145 450р.</s> 49 990р
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- акция вторая -->
            <div class="best__column">
                <div class="best__card">
                    <div class="best__pic">
                        <img src="./img/location/14.jpg" alt="111">
                        <div class="best__texts">
                            <h4 class="best__name">
                                Зал славы
                            </h4>
                            <p class="best__price">
                                <s>75 450р.</s> 45 990р
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- акция третья -->
            <div class="best__column">
                <div class="best__card">
                    <div class="best__pic">
                        <img src="./img/location/24.jpg" alt="111">
                        <div class="best__texts">
                            <h4 class="best__name">
                                Чаша любви
                            </h4>
                            <p class="best__price">
                                <s>45 750р.</s> 25 450р
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>
    <!-- секция подвала -->
    <footer class="footer">
        <div class="container">
            <!-- название -->
            <div class="footer__wrap">
                        <p class="footer__copyright">
                Праздник в каждый дом © 2024 Все права защищены
            </p>
    <!-- иконки социальных сетей -->
            <div class="footer__icons">
                <ul class="footer__icons-list">
                    <li class="footer__icon">
                        <img src="../img/icons/facebook.svg" alt="icon">
                    </li>
                    <li class="footer__icon">
                        <img src="../img/icons/vk.svg" alt="icon">
                    </li>
                    <li class="footer__icon">
                        <img src="../img/icons/instagram.svg" alt="icon">
                    </li>
                </ul>
            </div>
            <p class="text footer__politic">
                Политика конфиденциальности
            </p>   
            </div>
        </div>
    </footer>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    li {
        list-style: none;
    }
    a {
        text-decoration: none;
    }
    
    .container {
        max-width: 1400px;
        margin: 0 auto;
    }
    /* установка шрифта/ов */
    @font-face {
        font-family: Raleway;
        src: url('../fonts/Raleway-Regular.ttf')
    }
    
    body {
        font-family: Raleway;
    }
    /* установка текстовых значений */
    .title {
        font-size: 46px;
        font-weight: 900;
        margin-top: 50px;
    }
    .text {
        font-size: 22px;
        font-weight: 400;
    }
    /* установка стилей кнопок */
    .btn {
        color: #fff;
        background-color: #000;
        border-radius: 40px;
        padding: 10px 25px;
        justify-self: start;
        
    }
    /* установка анимации для кнопок при наведении */
    .btn:hover{
        background-color: #c32525;
        transition: all 1s ease;
    }
    /* header (головная часть) */
    /* установка позиции элементов */
    .header {
        padding: 20px 0;
        position: relative;
    }
    .header__wrap {
        display: flex;
        align-items: center;
    }
    
    .header__logo{
        margin-right: 80px;
    }
    
    .header__list, .header__icons-list{
        display: flex;
    }
    
    .header__list li{
        margin-right: 20px;
    }
    
    .header__link{
        color: black;
        font-weight: 700;
    }
    /* установка анимации для элементов при наведении */
    .header__link:hover{
        color: #c32525;
        border-bottom: 2px solid #c32525;
        transition: all 0.3s ease;
    }
    /* установка положения иконок */
    .header__icons {
        margin: 0 0 0 auto;
    }
    .header__icon {
        margin-left: 20px;
    }
    
    /* best */
    /* установка позиций */
    .best{
        padding: 100px 0;
    }
    
    .best__head{
        display: flex;
        align-items: flex-end;
        justify-content: space-between;
        margin-bottom: 50px;
    }
    /* установка позиции заголовка */
    .best__title{
        margin-top: -80px;
    }
    
    .best__link{
        color: #000;
        font-weight: 700;
        padding-bottom: 7px;
    }
    /* установка анимации при наведении */
    .best__link:hover{
        color: #c32525;
        border-bottom: 2px solid #c32525;
        transition: all 0.3 ease;
    }
    
    .best__row{
        display: flex;
        margin: 0 -35px;
    }
    
    .best__column{
        padding: 0 35px;
    }
    
    .best__card{
        transition: all 0.3s ease;  
    }
    
    .best__card:hover{
        transform: scale(1.1);
        transition: all 0.3s ease;  
    }
    /* установка позиции текста */
    .best__texts{
        display: flex;
        justify-content: space-between;
        padding: 10px;
    }
        /* footer (подвал) */
    /* установка позиций подвала */
    .footer {
    position: fixed;
    bottom: 10px;
    left: 0;
    width: 100%;
    }
    
    .footer__wrap{
        display: flex;
        justify-content: space-between;
    }
    /* установка позиции и анимации иконок */
    .footer__icons-list{
        display: flex;
        margin: 0 0 0 auto;
    }
    
    .footer__icon {
        margin-left: 20px;
        transition: all 0.3s ease;
    }
    .footer__icon:hover{
        transform: scale(1.3);
        transition: all 0.3s ease;
    }
    .footer__politic:hover{
        color: #c32525;
        transition: all 0.3s ease;
    }
    button {
  border: none;
  background-color:#fff;
    }
    </style>
<script>
    function goHome() {
        window.location.href = "/";
    }
</script>