<!DOCTYPE html>
<html lang="ru">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link rel="stylesheet" href="https://unpkg.com/swiper@8/swiper-bundle.min.css">
   <link rel="stylesheet" href="css/style.css">
   <title>Аренда квартир</title>
</head>
<body>
   <header class="header">
      <div class="container">
            <div class="header__nav-bar">
               <button class="header__burger f-cc" type="button"><span> </span></button>
               <div class="header__logo"><img src="img/logo.svg" alt="Logo"></div>
               <ul class="header__nav">
                  <li class="header__nav-item"><a href="#">Главная</a></li>
                  <li class="header__nav-item"><a href="apartments.html">Квартиры</a></li>
                  <li class="header__nav-item"><a href="#contacts">Контакты</a></li>
                  <li class="header__nav-item"><a href="#about">О нас</a></li>
               </ul>
               <div class="header__contacts">
                  <a class="header__contacts-item" href="mailto:mail@mail.ru"><div class="header__contacts-icon f-cc"><img src="img/icons/mail.svg" alt="mail"></div><p>mail@mail.ru</p></a>
                  <a class="header__contacts-item" href="tel:+78000000000"><div class="header__contacts-icon f-cc"><img src="img/icons/phone.svg" alt="phone"></div><p>+7 (800) 000-00-00</p></a>
               </div>
               <button class="header__btn btn js-open-popup" type="button">Обратная связь</button>
            </div>
      </div>
   </header>
   <main class="main">
      <section class="rent">
         <div class="container">
            <div class="rent__body">
               <div class="rent__txt-wrapper">
                  <div class="rent__txt">
                     <h1 class="rent__title">Аренда квартир</h1>
                     <p class="rent__sub-title"><span>Посуточно или&nbsp;на&nbsp;длительный&nbsp;срок</span></p>
                     <a class="rent__btn btn" href="apartments.html">Смотреть варианты</a>
                  </div>
               </div>
            </div>
         </div>
         <div class="rent__img">
            <img src="img/rent-img.jpg" alt="apartments">
         </div>
      </section>
      <section class="advantage">
         <div class="container">
            <ul class="advantage__list">
               <li class="advantage__item">
                  <img src="img/rent-advantage/documentation.svg" alt="documentation">
                  <p>Заключаем договоры, предоставляет отчётные документы</p>
               </li>
               <li class="advantage__item">
                  <img src="img/rent-advantage/money.svg" alt="payment">
                  <p>Наличный и безналичный расчёт</p>
               </li>
               <li class="advantage__item">
                  <img src="img/rent-advantage/time.svg" alt="time">
                  <p>Бронирование и заселение круглосуточно</p>
               </li>
               <li class="advantage__item">
                  <img src="img/rent-advantage/safety.svg" alt="safety">
                  <p>Полная конфиденциальность</p>
               </li>
            </ul>
         </div>
      </section>
      <section class="quarters">
         <div class="container">
            <h2 class="h2">Наши квартиры</h2>
            <div class="quarters__body">
               <div class="quarters__room-wrapper first-child">
                  <div class="quarters__room ">
                     <div class="quarters__photo">
                        <img src="img/quarters/1.jpg" alt="room photo">
                     </div>
                     <p class="quarters__feature-m">1 комната</p>
                     <p class="quarters__feature-d">Однокомнатная квартира</p>
                     <p class="quarters__price">Сутки: <span>1 500 ₽</span></p>
                     <div class="quarterrs__footer">
                        <button class="quarters__adress">ул. Юбилейная 108</button>
                        <a class="quarters__btn btn" href="flat.html">Подробней</a>
                     </div>
                  </div>
               </div>
               <div class="quarters__room-wrapper">
                  <div class="quarters__room">
                     <div class="quarters__photo">
                        <img src="img/quarters/2.jpg" alt="room photo">
                     </div>
                     <p class="quarters__feature-m">2 комнаты</p>
                     <p class="quarters__feature-d">Двухкомнатная квартира</p>
                     <p class="quarters__price">Сутки: <span>1 300 ₽</span></p>
                     <div class="quarterrs__footer">
                        <button class="quarters__adress">ул. Гагарина 89</button>
                        <a class="quarters__btn btn" href="flat.html">Подробней</a>
                     </div>
                  </div>
               </div>
               <div class="quarters__room-wrapper">
                  <div class="quarters__room">
                     <div class="quarters__photo">
                        <img src="img/quarters/3.jpg" alt="room photo">
                     </div>
                     <p class="quarters__new">Новая квартира</p>
                     <p class="quarters__feature-m">3 комнаты</p>
                     <p class="quarters__feature-d">Трёхкомнатная квартира</p>
                     <p class="quarters__price">Сутки: <span>1 700 ₽</span></p>
                     <div class="quarterrs__footer">
                        <button class="quarters__adress"> ул. Шмидта 10</button>
                        <a class="quarters__btn btn" href="flat.html">Подробней</a>
                     </div>
                  </div>
               </div>
               <div class="quarters__room-wrapper last-child">
                  <div class="quarters__room">
                     <div class="quarters__photo">
                        <img src="img/quarters/5.jpg" alt="room photo">
                     </div>
                     <p class="quarters__feature-m">5 комнат</p>
                     <p class="quarters__feature-d">Пятикомнатная квартира</p>
                     <p class="quarters__price">Сутки: <span>4 100 ₽</span></p>
                     <div class="quarterrs__footer">
                        <button class="quarters__adress">ул. Власова 14</button>
                        <a class="quarters__btn btn" href="flat.html">Подробней</a>
                     </div>
                  </div>
               </div>
            </div>
            <a class="quarters__btn-all btn" href="apartments.html">Смотреть все квартиры</a>
         </div>
      </section>
      <section class="about" id="about">
         <div class="container">
            <h2 class="h2">О нас</h2>
            <div class="about__body">
               <div class="about__txt">Сегодня мы — одна из крупнейших в крае гостиничных сетей, динамично расширяющая географический охват и повышающая качество сервиса.</div>
               <div class="about__content">
                  <div class="about__card">
                     <img class="about__img" src="img/about-us/deal.svg" alt="deal">
                     <div class="about__showing">
                        <p class="h2">40+</p>
                        <p class="about__txt">Клиентов</p>
                     </div>
                  </div>
                  <div class="about__card">
                     <img class="about__img" src="img/about-us/review.svg" alt="review">
                     <div class="about__showing">
                        <p class="h2">100+</p>
                        <p class="about__txt">Отзывов</p>
                     </div>
                  </div>
                  <div class="about__card">
                     <img class="about__img" src="img/about-us/home.svg" alt="home">
                     <div class="about__showing">
                        <p class="h2">9</p>
                        <p class="about__txt">Квартир</p>
                     </div>
                  </div>
               </div>
            </div>
            <div class="border-line"> </div>
         </div>
      </section>
      <section class="contacts" id="contacts">
         <div class="container">
            <div class="contacts__body">
               <h2 class="h2">Контакты</h2>
               <div class="contacts__txt">
                  <p class="contacts__adress">Адрес нашего офиса: ...</p>
                  <a class="contacts__mail" href="mailto:mail@mail.ru"> mail@mail.ru</a>
                  <a class="contacts__tel" href="tel:+78000000000">+7 (800) 000-00-00</a>
                  <a class="contacts__insta" href="#">Жизнь нашей гостиницы</a>
                  <a class="contacts__vk" href="#">Актуальные новости</a>
               </div>
            </div>
            <div class="contacts__map">
               <div style="overflow:hidden;"><a href="https://yandex.ru/maps?utm_medium=mapframe&utm_source=maps" style="color:#eee;font-size:12px;position:absolute;top:0px;">Яндекс Карты</a><a href="https://yandex.ru/maps/?ll=37.739780%2C55.658705&utm_medium=mapframe&utm_source=maps&z=8.46" style="color:#eee;font-size:12px;position:absolute;top:14px;">Россия — Яндекс Карты</a><iframe src="https://yandex.ru/map-widget/v1/-/CCUFeRCXsA" width="100%" height="450" frameborder="1" allowfullscreen="true" style="position:relative;"></iframe></div>
            </div>
         </div>
      </section>
      <section class="reviews">
         <div class="container">
            <div class="reviews__body">
               <h2 class="h2">Отзывы клиентов</h2>
               <div class="swiper slider-swiper">
                  <div class="swiper-wrapper">
                     <div class="swiper-slide">
                        <article class="reviews-card feedback">
                           <h3 class="feedback__title">Верстка сайтов!</h3>
                           <p class="feedback__txt">Качественно, недорого, в сжатые сроки - Выберете любые два пункта. Взаимовыгодное сотрудничество! </p>
                           <p class="feedback__name">Верстальщик Сайтов</p>
                           <div class="feedback__footer">
                           <p class="feedback__city">г. Город</p>
                           <time class="feedback__date" datetime="2022-04-26">26 апреля 2022</time>
                           </div>
                        </article>
                     </div>
                     <div class="swiper-slide">
                        <article class="reviews-card feedback">
                           <h3 class="feedback__title">Уютная квартира</h3>
                           <p class="feedback__txt">Первый раз отдыхали у вас, времени было мало соответственно жильё искали заранее. Залог вносили с опасением, и очень рады что они были напрасными. Всё супер. Нам понравилось!</p>
                           <p class="feedback__name">Иван Иванов</p>
                           <div class="feedback__footer">
                           <p class="feedback__city">г. Пермь</p>
                           <time class="feedback__date" datetime="2021-01-05">5 января 2021</time>
                           </div>
                        </article>
                     </div>
                     <div class="swiper-slide">
                        <article class="reviews-card feedback">
                           <h3 class="feedback__title">Красивый вид на город</h3>
                           <p class="feedback__txt">Благодарю за квартиру. Удобное месторасположение, совсем рядом с центром. Квартира уютная, соседей не слышно, мы прекрасно отдохнули.Все что нужно есть.</p>
                           <p class="feedback__name">Татьяна Бездомная</p>
                           <div class="feedback__footer">
                           <p class="feedback__city">г. Москва</p>
                           <time class="feedback__date" datetime="2021-03-08">8 марта 2021</time>
                           </div>
                        </article>
                     </div>
                     <div class="swiper-slide">
                        <article class="reviews-card feedback">
                           <h3 class="feedback__title">Просторная квартира</h3>
                           <p class="feedback__txt">Рыбатекст используется дизайнерами, проектировщиками и фронтендерами, когда нужно быстро заполнить макеты или прототипы содержимым. Это тестовый контент. </p>
                           <p class="feedback__name">Рыба Текст</p>
                           <div class="feedback__footer">
                           <p class="feedback__city">г. Рыбинск</p>
                           <time class="feedback__date" datetime="2021-04-01">1 апреля 2021</time>
                           </div>
                        </article>
                     </div>
                  </div>
                  <div class="swiper-pagination"></div>
                  </div>
            </div>
            <div class="swiper-btn-prev"></div>
            <div class="swiper-btn-next"></div>
         </div>
      </section>
      <section class="write-us">
         <div class="container">
            <div class="write-us__form-block">
               <div class="write-us__wrapper">
                  <h2 class="h2">Напишите нам</h2>
                  <form class="write-us__form" action="#">
                     <input class="write-us__name" type="text" name="name" placeholder="Имя">
                     <input class="write-us__email" type="email" name="email" placeholder="Email">
                     <textarea class="write-us__text" name="text" rows="4" placeholder="Ваше сообщение"></textarea>
                     <button class="btn" type="submit">Отправить</button>
                  </form>
               </div>
            </div>
            <div class="write-us__appeal">
               <p class="write-us__appeal-txt">Дорогой гость, если у тебя есть какие-то пожелания или притензии по улучшению качества обслуживания или просто хочешь оставить свой комментарий, то заполни форму. Мы обязательно ответим тебе, или опубликуем его на нашем сайте.</p>
               <p class="write-us__appeal-sign">Директор гостиницы</p>
            </div>
         </div>
      </section>
   </main>
   <footer class="footer">
      <div class="footer-wrapper">
         <div class="container">
            <div class="footer__logo"><img src="img/logo.svg" alt="Logo"></div>
            <ul class="footer__nav">
               <li class="footer__nav-item"><a href="#">Главная</a></li>
               <li class="footer__nav-item"><a href="#">Квартиры</a></li>
               <li class="footer__nav-item"><a href="#">Контакты</a></li>
               <li class="footer__nav-item"><a href="#">О нас</a></li>
            </ul>
            <div class="footer__contacts">
               <a class="footer__contacts-tel" href="tel:+78000000000"><p>+7 (800) 000-00-00</p></a>
               <a class="footer__contacts-mail" href="mailto:mail@mail.ru"><p>mail@mail.ru</p></a>
            </div>
            <div class="footer__social">
               <a class="footer__social-item" href="#">
                  <svg width="20" height="20" fill="none" xmlns="http://www.w3.org/2000/svg">
                     <circle cx="10" cy="10" r="10" fill="white"/>
                     <path d="M4.67535 10.1872L6.9744 11.0444L7.87063 13.928C7.9096 14.1228 8.1434 14.1618 8.29927 14.0449L9.58517 12.9928C9.70207 12.8759 9.89691 12.8759 10.0528 12.9928L12.3518 14.6683C12.5077 14.7852 12.7415 14.7073 12.7804 14.5125L14.495 6.32945C14.534 6.13462 14.3391 5.93978 14.1443 6.01772L4.67535 9.6806C4.44155 9.75853 4.44155 10.1092 4.67535 10.1872ZM7.75374 10.6158L12.2739 7.84915C12.3518 7.81019 12.4297 7.92709 12.3518 7.96606L8.64997 11.4341C8.53307 11.551 8.41616 11.7069 8.41616 11.9017L8.29927 12.8369C8.29927 12.9538 8.10443 12.9928 8.06547 12.8369L7.59786 11.1224C7.48096 10.9275 7.5589 10.6937 7.75374 10.6158Z" fill="#2B7AF1"/>
                     </svg>
               </a>
               <a class="footer__social-item" href="#">
                  <svg width="20" height="20" fill="none" xmlns="http://www.w3.org/2000/svg">
                     <circle cx="10" cy="10" r="10" fill="white"/>
                     <path d="M14.5 6.90945C14.5 6.16074 13.8394 5.50012 13.0907 5.50012H7.40932C6.66062 5.50012 6 6.16074 6 6.90945V12.5908C6 13.3395 6.66062 14.0001 7.40932 14.0001H10.272V10.7851H9.21503V9.37577H10.272V8.80323C10.272 7.83432 10.9767 6.99753 11.8575 6.99753H13.0026V8.40685H11.8575C11.7254 8.40685 11.5933 8.53898 11.5933 8.80323V9.37577H13.0026V10.7851H11.5933V14.0001H13.0907C13.8394 14.0001 14.5 13.3395 14.5 12.5908V6.90945Z" fill="#2B7AF1"/>
                     </svg>
               </a>
               <a class="footer__social-item" href="#">
                  <svg width="20" height="20" fill="none" xmlns="http://www.w3.org/2000/svg">
                     <circle cx="10" cy="10" r="10" fill="white"/>
                     <path d="M14.903 12.5575C14.903 12.516 14.8615 12.516 14.8615 12.4745C14.6954 12.1424 14.3218 11.7273 13.8237 11.2707C13.5746 11.0631 13.4501 10.897 13.3671 10.814C13.2425 10.648 13.2426 10.5234 13.2841 10.3574C13.3256 10.2329 13.4916 10.0253 13.7822 9.6517C13.9482 9.44414 14.0313 9.31961 14.1558 9.19508C14.7785 8.36485 15.069 7.8252 14.986 7.57613L14.9445 7.53462C14.903 7.49311 14.8615 7.4516 14.7785 7.4516C14.6954 7.41009 14.5709 7.41009 14.4464 7.4516H12.8689C12.8274 7.4516 12.8274 7.4516 12.7444 7.4516C12.7029 7.4516 12.6614 7.4516 12.6614 7.4516H12.6199H12.5784L12.5368 7.49311C12.4953 7.53462 12.4953 7.53462 12.4953 7.57613C12.3293 8.03276 12.1217 8.40636 11.9142 8.82147C11.7896 9.02903 11.6651 9.23659 11.5406 9.40264C11.416 9.56868 11.333 9.69322 11.25 9.77624C11.167 9.85926 11.0839 9.90077 11.0424 9.9838C11.0009 10.0253 10.9179 10.0668 10.9179 10.0253C10.8764 10.0253 10.8349 10.0253 10.8349 9.9838C10.7934 9.94228 10.7519 9.90077 10.7103 9.85926C10.6688 9.81775 10.6688 9.73473 10.6273 9.6517C10.6273 9.56868 10.6273 9.48566 10.6273 9.44414C10.6273 9.40263 10.6273 9.2781 10.6273 9.19508C10.6273 9.07055 10.6273 8.98752 10.6273 8.94601C10.6273 8.82147 10.6273 8.65543 10.6273 8.48939C10.6273 8.32334 10.6273 8.1988 10.6273 8.11578C10.6273 8.03276 10.6273 7.90822 10.6273 7.8252C10.6273 7.70067 10.6273 7.61764 10.6273 7.57613C10.6273 7.53462 10.5858 7.4516 10.5858 7.41009C10.5443 7.36857 10.5028 7.32706 10.4613 7.28555C10.4198 7.24404 10.3367 7.24404 10.2952 7.20253C10.0877 7.16102 9.83861 7.11951 9.54803 7.11951C8.88385 7.11951 8.42722 7.16102 8.26117 7.24404C8.17815 7.28555 8.09513 7.32706 8.05362 7.41009C7.97059 7.49311 7.97059 7.53462 8.0121 7.53462C8.21966 7.57613 8.38571 7.65915 8.46873 7.78369L8.51025 7.86671C8.55176 7.90823 8.55175 7.99125 8.59326 8.11578C8.63477 8.24031 8.63477 8.36485 8.63477 8.53089C8.63477 8.77996 8.63477 9.02903 8.63477 9.19508C8.63477 9.40264 8.59326 9.52717 8.59326 9.6517C8.59326 9.77624 8.55176 9.85926 8.51025 9.90077C8.46873 9.9838 8.46873 10.0253 8.42722 10.0253C8.42722 10.0253 8.42722 10.0668 8.3857 10.0668C8.34419 10.0668 8.30268 10.1083 8.21966 10.1083C8.17815 10.1083 8.09513 10.0668 8.05362 10.0253C7.97059 9.9838 7.88757 9.90077 7.84606 9.81775C7.76304 9.73473 7.68001 9.61019 7.59699 9.44414C7.51397 9.2781 7.38943 9.11206 7.3064 8.86299L7.22339 8.69694C7.18188 8.61392 7.09885 8.44787 7.01583 8.24032C6.93281 8.03276 6.84978 7.86671 6.76676 7.65916C6.72525 7.57613 6.68374 7.53462 6.64223 7.49311H6.60072C6.60072 7.49311 6.5592 7.4516 6.51769 7.4516C6.47618 7.4516 6.43467 7.41009 6.39316 7.41009H4.89874C4.7327 7.41009 4.64968 7.4516 4.60816 7.49311L4.56665 7.53462C4.56665 7.53462 4.56665 7.57613 4.56665 7.61764C4.56665 7.65915 4.56665 7.70066 4.60816 7.78369C4.81572 8.28182 5.06479 8.77996 5.31386 9.2781C5.56293 9.73473 5.812 10.1498 5.97804 10.4404C6.1856 10.731 6.35164 11.0216 6.5592 11.2707C6.76676 11.5197 6.89129 11.6858 6.9328 11.7688C7.01583 11.8518 7.05733 11.8933 7.09885 11.9348L7.22339 12.0594C7.30641 12.1424 7.43094 12.2669 7.59699 12.3915C7.76303 12.516 7.97059 12.6405 8.17815 12.7651C8.3857 12.8896 8.63478 12.9726 8.88385 13.0556C9.17443 13.1387 9.42349 13.1802 9.67256 13.1387H10.2952C10.4198 13.1387 10.5028 13.0972 10.5858 13.0141L10.6273 12.9726C10.6273 12.9311 10.6688 12.9311 10.6688 12.8896C10.6688 12.8481 10.6688 12.8066 10.6688 12.7236C10.6688 12.5575 10.6688 12.433 10.7103 12.3084C10.7519 12.1839 10.7519 12.1009 10.7934 12.0179C10.8349 11.9348 10.8764 11.8933 10.9179 11.8518C10.9594 11.8103 11.0009 11.7688 11.0009 11.7688H11.0424C11.1255 11.7273 11.25 11.7688 11.333 11.8518C11.4576 11.9348 11.5821 12.0594 11.6651 12.1839C11.7481 12.3084 11.8727 12.433 12.0387 12.599C12.2048 12.7651 12.3293 12.8896 12.4123 12.9311L12.5368 13.0141C12.6199 13.0556 12.7029 13.0972 12.8274 13.1387C12.952 13.1802 13.035 13.1802 13.118 13.1802L14.5294 13.1387C14.6539 13.1387 14.7785 13.0972 14.8615 13.0556C14.9445 13.0141 14.986 12.9726 14.986 12.8896C14.986 12.8481 14.986 12.7651 14.986 12.7236C14.903 12.6405 14.903 12.599 14.903 12.5575Z" fill="#2B7AF1"/>
                     </svg>
               </a>
               <a class="footer__social-item" href="#">
                  <svg width="20" height="20" fill="none" xmlns="http://www.w3.org/2000/svg">
                     <circle cx="10" cy="10" r="10" fill="white"/>
                     <path d="M13.2904 6.00012H7.20961C6.52308 6.00012 6 6.5232 6 7.20974V13.2905C6 13.977 6.52308 14.5001 7.20961 14.5001H13.2904C13.9769 14.5001 14.5 13.977 14.5 13.2905V7.20974C14.5 6.5232 13.9769 6.00012 13.2904 6.00012ZM10.25 12.8001C11.6558 12.8001 12.8 11.6886 12.8 10.3482C12.8 10.1194 12.7673 9.85781 12.7019 9.66166H13.4212V13.127C13.4212 13.2905 13.2904 13.454 13.0942 13.454H7.40577C7.24231 13.454 7.07885 13.3232 7.07885 13.127V9.62897H7.83077C7.76539 9.85781 7.73269 10.0867 7.73269 10.3155C7.7 11.6886 8.84423 12.8001 10.25 12.8001ZM10.25 11.8194C9.33462 11.8194 8.61538 11.1001 8.61538 10.2174C8.61538 9.33474 9.33462 8.61551 10.25 8.61551C11.1654 8.61551 11.8846 9.33474 11.8846 10.2174C11.8846 11.1328 11.1654 11.8194 10.25 11.8194ZM13.3885 8.32128C13.3885 8.51743 13.225 8.68089 13.0288 8.68089H12.1135C11.9173 8.68089 11.7538 8.51743 11.7538 8.32128V7.43858C11.7538 7.24243 11.9173 7.07897 12.1135 7.07897H13.0288C13.225 7.07897 13.3885 7.24243 13.3885 7.43858V8.32128Z" fill="#2B7AF1"/>
                     </svg>
               </a>
            </div>
         </div>
      </div>
   </footer>
   <div class="popup">
      <div class="callback-container">
         <div class="callback">
            <button class="close-btn">закрыть</button>
            <h2 class="h2">Заказать звонок</h2>
            <div class="callback__txt">Оставьте заявку и мы свяжемся с Вами в ближайшее время!</div>
            <form class="callback__form">
               <input class="callback__name" type="text" name="callback__name" placeholder="Имя">
               <input class="callback__tel" type="tel" name="callback__tel" placeholder="Телефон">
               <button class="btn" type="submit">Отправить</button>
            </form>
         </div>
      </div>
   </div>
   <script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script>
   <script src="js/script.js"></script>
</body>
</html>
