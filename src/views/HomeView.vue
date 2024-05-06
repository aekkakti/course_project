<template>
    <!doctype html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport"
              content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <link rel="stylesheet" href="../assets/css/assets.css">
        <title>Автомастерская</title>
    </head>

    <body>
    <section class="aboutCompany">
        <div class="wrapper">
            <div class="d-f f-d-c a-i-c">
                <h2 class="c-w fs-48px">Элисса</h2>
                <h3 class="c-y fs-32px">Профессионалы в сфере обслуживания автомобильного транспорта</h3>
                <h3 class="c-w fs-32px">Более 6 лет качественного обслуживания</h3>
            </div>
        </div>
    </section>

    <section class="ourServices">
        <div class="wrapper">
            <div class="d-f j-c-c">
                <h2 class="fs-32px">Мы предоставляем экспертные услуги</h2>
            </div>
            <div class="d-f j-c-c mt-1">
                <h3 class="fs-17px fw-400">Мы стремимся завоевать ваше доверие и иметь долгосрочные
                    отношения с вами
                </h3>
            </div>
            <div class="d-f f-d-r j-c-c gap_13 mt_3">
                <div class="d-f f-d-c">
                    <div class="d-f a-i-c j-c-c">
                        <img src="../assets/img/sales-icon.png" alt="Нет изображения" loading="lazy"/>
                    </div>
                    <h3 class="fs-17px fw-400">Акции и скидки</h3>
                </div>

                <div class="d-f f-d-c">
                    <div class="d-f a-i-c j-c-c">
                        <img src="../assets/img/advantage-icon.png" alt="Нет изображения" loading="lazy"/>
                    </div>
                    <h3 class="fs-17px fw-400">Наши преимущества</h3>
                </div>

                <div class="d-f f-d-c">
                    <div class="d-f a-i-c j-c-c">
                        <img src="../assets/img/key_icon.png" alt="Нет изображения" loading="lazy"/>
                    </div>
                    <h3 class="fs-17px fw-400">О нас</h3>
                </div>

            </div>
        </div>
    </section>

    <section class="whatWeGive mt_3">
        <div class="wrapper mt-1 c-w">
            <div class="d-f f-d-r">
                <h3 class="fs-32px">О&nbsp;нашей&nbsp;</h3>
                <h3 class="fs-32px c-y">компании</h3>
            </div>
            <h3 class="whatWeUse mt-1">Мы используем передовое оборудование для обеспечения обслуживания
                наивысшего уровня на всем рынке
            </h3>
            <ul class="d-f f-d-c t-a-l">
                <li>2 года гарантии</li>
                <li>Бесплатная диагностика</li>
                <li>Реферальная программа для клиентов</li>
                <li>Постоянные скидки и акции</li>
                <li>Ежедневная помощь на дороге</li>
                <li>Сертифицированный сервис</li>
            </ul>
            <img class="two_people_image" loading="lazy" alt="Нет" src="../assets/img/two-people-image.png"/>
        </div>
    </section>

    <section class="howWeMakeService mt_3">
        <div class="wrapper">
            <h3 class="fs-32px d-f j-c-c">Как происходит обслуживание</h3>
            <div class="d-f f-d-r j-c-c">
                <figure>
                    <img class loading="lazy" alt="Нет" src="../assets/img/chooseService-icon.png"/>
                    <figcaption class="d-f t-a-c">Выберите услугу, которая вас интересует</figcaption>
                </figure>
                <figure>
                    <img class loading="lazy" alt="Нет" src="../assets/img/sendRequest-icon.png"/>
                    <figcaption class="d-f t-a-c j-c-c">Оставьте заявку</figcaption>
                </figure>
                <figure>
                    <img class loading="lazy" alt="Нет" src="../assets/img/deliveryCar-icon.png"/>
                    <figcaption class="d-f t-a-c">Доставим ваше авто в сервис и займемся ремонтом</figcaption>
                </figure>
                <figure>
                    <img class loading="lazy" alt="Нет" src="../assets/img/getKey-icon.png"/>
                    <figcaption class="d-f t-a-c">Получите ключи от вашего востановленного автомобиля</figcaption>
                </figure>
            </div>
        </div>
    </section>

    <section class="usersReviews">
        <div class="wrapper">

        </div>
    </section>


    <!-- доделать нужно секцию с отзывами,галереей -->


    <section class="sendForm mt_3">
        <div class="wrapper mt-1">
            <h2 class="fs-32px c-w d-f j-c-c pt-2">Хотите оставить заявку? Эта форма - для Вас!</h2>
            <div class="mt_3">
                <div class="sendRequestForm">
                    <h3 class="fs-24px">Форма для записи</h3>
                    <label for="surname_name" class="fs-17px">Имя, фамилия</label><br><br>
                    <input id="surname_name" class="fs-17px" type="text" placeholder="Иванов Иван" required><br><br><br>

                    <label for="chooseService" class="fs-17px">Услуга</label><br><br>
                    <select id="chooseService" class="fs-17px" required>
                        <option value="">Профилактическое обслуживание</option>
                        <option value="">Ремонт трансмиссии</option>
                        <option value="">Обслуживание и ремонт двигателя</option>
                        <option value="">Обслуживание и ремонт тормозов</option>
                        <option value="">Обслуживание электронники</option>
                        <option value="">Обслуживание системы зажигания</option>
                        <option value="">Услуги детейлинга</option>
                        <option value="">Обслуживание топливной системы</option>
                    </select><br><br><br>

                    <label for="putPhoneNumber" class="fs-17px">Номер телефона</label><br><br>
                    <input id="putPhoneNumber" class="fs-17px" type="tel" placeholder="+7-952-986-65-00"><br><br><br>

                    <label for="putCouponNumber" class="fs-17px">Номер дружественного купона</label><br><br>
                    <input id="putCouponNumber" class="fs-17px" type="number" placeholder="9481927583910"><br><br><br>

                    <label for="putAdditionally" class="fs-17px">Дополнительно</label><br><br>
                    <input id="putAdditionally" class="fs-17px" type="text"><br><br><br>
                    <button type="submit" class="sendFormButton d-f a-i-c fs-24px">Отправить</button>
                </div>
            </div>
        </div>
    </section>

    </body>
    </html>
</template>
