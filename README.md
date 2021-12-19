kuternega.github.io/kurdia.github.io

<!DOCTYPE html>
<html lang="ru">

<head>
  <title>Coo-project</title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>

<body>
  <header>
    <section class="col-12">
      <video id="bg_video" autoplay="autoplay" loop="" preload="auto" muted="">
        <source src="pictures/video.mp4" type="video/mp4">
      </video>
    </section>
    <section id="header_section" class="col-12 collumn">

      <div id="header_links" class="row col-9 mx-auto">
        <div id="header_logo" class="col-3 pt-2">
          <img src="pictures/initlab.svg" alt="Основная страница" width="156" height="31" />
        </div>
        <div id="list_of_links" class="row col-9 mx-auto">
          <div class="txt_top mx-auto" onMouseOver="showBorder(this)" onmouseout="    hideBorder(this)">ПОДДЕРЖКА DRUPAL</div>
          <div onMouseOver="showBlock()" onmouseout="hideBlock()" class="txt_top mx-auto" >
            АДМИНИСТРИРОВАНИЕ
            <div id="admin_block" onMouseOver="showBlock()" onmouseout="hideBlock()">
              <div id="admin_inside">
                <div class="admin_txt col-12 px-0" onMouseOver="becomeDarker(this)" onMouseOut="becomeBrighter(this)"><a class="admin_clr" href="">МИГРАЦИЯ</a></div>
                <div class="admin_txt col-12 px-0" onMouseOver="becomeDarker(this)" onMouseOut="becomeBrighter(this)"><a class="admin_clr" href="">БЭКАПЫ</a></div>
                <div class="admin_txt col-12 px-0" onMouseOver="becomeDarker(this)" onMouseOut="becomeBrighter(this)"><a class="admin_clr" href="">АУДИТ БЕЗОПАСНОСТИ</a></div>
                <div class="admin_txt col-12 px-0" onMouseOver="becomeDarker(this)" onMouseOut="becomeBrighter(this)"><a class="admin_clr" href="">ОПТИМИЗАЦИЯ СКОРОСТИ</a></div>
                <div class="admin_txt col-12 px-0" onMouseOver="becomeDarker(this)" onMouseOut="becomeBrighter(this)"><a class="admin_clr" href="">ПЕРЕЕЗД НА HTTPS</a></div>
              </div>
            </div>  
          </div>
          <div class="txt_top mx-auto" onMouseOver="showBorder(this)" onmouseout="hideBorder(this)">ПРОДВИЖЕНИЕ</div>
          <div class="txt_top mx-auto" onMouseOver="showBorder(this)" onmouseout="hideBorder(this)">РЕКЛАМА</div>
          <div class="txt_top mx-auto" onMouseOver="showBorder(this)" onmouseout="hideBorder(this)">О НАС</div>
          <div class="txt_top mx-auto" onMouseOver="showBorder(this)" onmouseout="hideBorder(this)">ПРОЕКТЫ</div>
          <div class="txt_top mx-auto" onMouseOver="showBorder(this)" onmouseout="hideBorder(this)">КОНТАКТЫ</div>
        </div>
      </div>

      <div id="razr_block" class="row mx-auto col-sm-12 col-md-12 col-lg-9 col-xl-9">
        <div class="tarifs_link mx-auto col-xl-6 col-lg-6 col-md-12 col-sm-12">
          <div id="razr" class="col-12 mx-sm-auto mx-md-auto mx-lg-0 mx-xl-0 mb-4">Разработка<br />сайтов на Drupal</div>
          <div id="uslugi" class="col-12 ">Услуги разработки и поддержки сайтов<br />на Drupal, работаем с 2005 года</div>
          <div id="btn_block" class="col-sm-8 col-md-6 col-lg-7 col-xl-7">
            <button id="btn_frst" class="mx-auto">ТАРИФЫ</button>
          </div>
        </div>
          
        <div id="gs" class="row mx-auto col-sm-12 col-md-12 col-lg-6 col-xl-6">
          <div class="gs_tripple row col-sm-6 col-md-6 col-lg-12 col-xl-12 my-lg-auto my-xl-auto">
            <div class="gs_block col-sm-12 col-md-12 col-lg-4 col-xl-4">
              <div class="gs_up_first row col-12">
                #1
                <img id="trophy" src="pictures/cup.png" alt="Кубок" height="58" width="59"/>
              </div>
              <div class="gs_down">Drupal-разработчик<br />в России по версии<br />Рейтинга Рунета</div>
            </div>

            <div class="gs_block col-sm-12 col-md-12 col-lg-4 col-xl-4">
              <div class="gs_up_second">3+</div>
              <div class="gs_down">средний опыт<br />специалистов более<br />3 лет</div>
            </div>

            <div class="gs_block col-sm-12 col-md-12 col-lg-4 col-xl-4">
              <div class="gs_up_second">14</div>
              <div class="gs_down">лет опыта в сфере<br />Drupal</div>
            </div>
          </div>

          <div class="gs_tripple row col-sm-6 col-md-6 col-lg-12 col-xl-12 my-lg-auto my-xl-auto">
            <div class="gs_block col-sm-12 col-md-12 col-lg-4 col-xl-4">
              <div class="gs_up_second">50+</div>
              <div class="gs_down">модулей и тем<br />в формате DrupalGive</div>
            </div>

            <div class="gs_block col-sm-12 col-md-12 col-lg-4 col-xl-4">
              <div class="gs_up_second">90 000+</div>
              <div class="gs_down">часов поддержки<br />сайтов на Drupal</div>
            </div>

            <div class="gs_block col-sm-12 col-md-12 col-lg-4 col-xl-4">
              <div class="gs_up_second">300+</div>
              <div class="gs_down">проектов<br />на поддержке</div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>

  <div id="wht" class="col-12 px-0">
    <div id="wht_block">
      <div class="row col-sm-12 col-md-12 col-lg-9 col-xl-9 mx-auto mb-sm-4 mb-md-4">
        <div class="collumn col-md-6 px-0">
          <div id="wht_txt_up" class="mb-4">14 лет совершенствуем<br />компетенции в Drupal<br />разработке!</div>
          <div id="wht_txt_down" class="mb-5">Разрабатываем и оптимизируем модули, расширяем<br />функциональность сайтов, обновляем дизайн</div>
        </div>
      </div>

      <div class="wht_imgs row col-sm-12 col-md-12 col-lg-9 col-xl-9">
        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-1.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Добавление<br />информации на сайт,<br />создание новых<br />разделов</div>
        </div>

        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-2.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Разработка<br />и оптимизация<br />модулей сайта</div>
        </div>

        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-3.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Интеграция с CRM,<br />1C, платежными<br />системами, любыми<br />веб-сервисами</div>
        </div>

        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-4.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Любые доработки<br />функционала<br />и дизайна</div>
        </div>
      </div>


      <div class="wht_imgs row col-sm-12 col-md-12 col-lg-9 col-xl-9">
        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-5.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Аудит и мониторинг<br />безопасности Drupal<br />сайтов</div>
        </div>

        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-6.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Миграция, импорт<br />контента и апгрейд<br />Drupal</div>
        </div>

        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-7.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Оптимизация<br />и ускорение<br />Drupal-сайтов</div>
        </div>

        <div class="wht_square">
          <div>
            <div class="wht_img_size">
              <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
              <img src="pictures/competency-8.svg" alt="picture" width="81" height="81"/>
            </div>  
          </div>
          <div class="wht_img_txt col-12">Веб-маркетинг,<br />консультации<br />и работы по SEO</div>
        </div>
      </div>
    </div>
  </div>


  <div id="crossing_block">
    <div id="blk_txt" class="mx-auto">Разработка<br />от Drupal-coder</div>

    <div class="collumn mx-auto">
      <div class="row col-sm-12 col-md-12 col-lg-8 col-xl-8 mx-auto">

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">01.</div>
          <div class="blk_first_words">Постановка задачи по Email</div>
          <div class="blk_second_words">Удобная и привычная модель постановки задач, при которой задачи фиксируются и никогда не теряются. </div>
          <img class="blk_corner_img" src="pictures/support1.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">02.</div>
          <div class="blk_first_words">Система Helpdesk – отчетность, прозрачность</div>
          <div class="blk_second_words">Возможность посмотреть все заявки в работе и отработанные часы в личном кабинете через браузер. </div>
          <img class="blk_corner_img" src="pictures/support2.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">03.</div>
          <div class="blk_first_words">Расширенная техническая поддержка</div>
          <div class="blk_second_words">Возможность организации расширенной техподдержки с 6:00 до 22:00 без выходных. </div>
          <img class="blk_corner_img" src="pictures/support3.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">04.</div>
          <div class="blk_first_words">Персональный менеджер проекта</div>
          <div class="blk_second_words">Ваш менеджер проекта всегда в курсе текущего состояния проекта и в любой момент готов ответить на любые вопросы. </div>
          <img class="blk_corner_img" src="pictures/support4.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

      </div>

      <div class="row col-sm-12 col-md-12 col-lg-8 col-xl-8 mx-auto mx-auto">

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">05.</div>
          <div class="blk_first_words">Удобные способы оплаты</div>
          <div class="blk_second_words">Безналичный расчет по договору или электронные деньги: WebMoney, Яндекс.Деньги, Paypal. </div>
          <img class="blk_corner_img" src="pictures/support5.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">06.</div>
          <div class="blk_first_words">Работаем с SLA и NDA</div>
          <div class="blk_second_words">Работа в рамках соглашений о конфиденциальности и об уровне качества работ. </div>
          <img class="blk_corner_img" src="pictures/support6.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">07.</div>
          <div class="blk_first_words">Штатные специалисты</div>
          <div class="blk_second_words">Надежные штатные специалисты, никаких фрилансеров. </div>
          <img class="blk_corner_img" src="pictures/support7.svg" alt="image_in_corner" height="84" width="84"/>
        </div>

        <div class="blk_img collumn mx-auto mb-sm-3 mb-md-3">
          <div class="blk_num">08.</div>
          <div class="blk_first_words">Удобные каналы связи</div>
          <div class="blk_second_words">Консультации по телефону, скайпу, в месенджерах. </div>
          <img class="blk_corner_img" src="pictures/support8.svg" alt="image_in_corner" height="84" width="84" />
        </div>

      </div>
    </div>
  </div>

  <section id="blk_cross">
    <div id="blk_back"class="col-12">
      <div class="blk_little_block mx-auto ">
        <div class="blk_ecspertiza col-8">Экспертиза в Drupal, опыт 14 лет!</div>

        <div class="row py-sm-auto py-md-auto">
          <div class="blk_ecsp_txt col-sm-12 col-md-12 col-lg-4 col-xl-4 ">Только системный подход – контроль версий, резервирование и тестирование!</div>
          <div class="blk_ecsp_txt col-sm-12 col-md-12 col-lg-4 col-xl-4">Только Drupal сайты, не берем на поддержку сайты на других CMS!</div>
        </div>

        <div class="row mt-lg-5 mt-xl-5">
          <div class="blk_ecsp_txt col-sm-12 col-md-12 col-lg-4 col-xl-4 mb-sm-2 mb-md-2">Участвуем в разработке ядра Drupal и модулей на Drupal.org, разрабатываем <a href="">свои модули Drupal</a></div>
          <div class="blk_ecsp_txt col-sm-12 col-md-12 col-lg-4 col-xl-4">Поддерживаем сайты на Drupal 5, 6, 7 и 8</div>
        </div>
      </div>
      <img id="laptop_img" src="pictures/laptop.png" alt="laptop" width="625" height="603" />
    </div>
  </section>

  <section id="tarifs_bg" class="container col-12">
    <div id="tarifs_blocks" class="collumn">

      <div id="tarifs_name" class="mx-auto  mb-4 col-12 pt-sm-5 pt-md-5">Тарифы</div>

      <div class="tarifs_block_collumns row col-sm-12 col-md-12 col-lg-9 col-xl-9 mx-auto">


        <div class="tarif_col_big mx-auto col-sm-12 col-md-12 col-lg-4 col-xl-4">
          <div class="tarif_col collumn mx-auto">
            <div class="priced_type">Стартовый</div>
            <div class="tarif_goals">Разработка и поддержка Drupal</div>
            <div class="tarif_goals">Консультации и работы по SEO</div>
            <div class="tarif_goals">Услуги дизайнера</div>
            <div class="tarif_goals">Неиспользованные оплаченные часы переносятся на следующий месяц</div>
            <div class="tarif_goals">Предоплата от 6 000 рублей в месяц</div>
            <button class="tarifs_btn col-12">СВЯЖИТЕСЬ С НАМИ!</button>
          </div>
        </div>

        <div class="tarif_col_big mx-auto col-sm-12 col-md-12 col-lg-4 col-xl-4">
          <div class="tarif_col collumn mx-auto">
            <div class="priced_type">Бизнес</div>
            <div class="tarif_goals">Разработка и поддержка Drupal</div>
            <div class="tarif_goals">Консультации и работы по SEO</div>
            <div class="tarif_goals">Услуги дизайнера</div>
            <div class="tarif_goals">Высокое время реакции - до 2 рабочих дней</div>
            <div class="tarif_goals">Неиспользованные оплаченные часы не переносятся</div>
            <div class="tarif_goals">Предоплата от 30 000 рублей в месяц</div>
            <button class="tarifs_btn col-12">СВЯЖИТЕСЬ С НАМИ!</button>
          </div>
        </div>

        <div class="tarif_col_big mx-auto col-sm-12 col-md-12 col-lg-4 col-xl-4">
          <div class="tarif_col collumn mx-auto">
            <div class="priced_type">VIP</div>
            <div class="tarif_goals">Разработка и поддержка Drupal</div>
            <div class="tarif_goals">Консультации и работы по SEO</div>
            <div class="tarif_goals">Услуги дизайнера</div>
            <div class="tarif_goals">Максимальное время реакции - в день обращения</div>
            <div class="tarif_goals">Неиспользованные оплаченные часы не переносятся</div>
            <div class="tarif_goals">Предоплата от 270 000 рублей в месяц</div>
            <button class="tarifs_btn col-12">СВЯЖИТЕСЬ С НАМИ!</button>
          </div>
        </div>
      </div>
      <div id="not_agree_tarif_phone" class="col-12 px-0 my-5">
          Вам не подходят наши тарифы? Оставьте<br />заявку и мы предложим вам индивидуальные<br />условия!<br />
      </div>
      <div id="not_agree_tarif" class="col-12 px-0 mt-5 mb-3">
          Вам не подходят наши тарифы? Оставьте заявку и мы<br />предложим вам индивидуальные условия!<br />
      </div>
      <div id="not_agree_tarif_down" class="mx-auto"><a>ПОЛУЧИТЬ ИНДИВИДУАЛЬНЫЙ ТАРИФ</a></div>
    </div>

 
    
  </section>



  <div id="skill_time" class="col-12">
    <div class="collumn col-sm-12 col-md-12 col-lg-8 col-xl-8 mx-auto">
      <div id="devs_time_skills">Наши профессиональные разработчики выполняют быстро любые задачи</div>
      <div class="row">

        <div class="skill_block col-sm-12 col-md-12 col-lg-4 col-xl-4 mx-sm-auto mx-md-auto">
          <div class="skill_img">
            <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
            <img src="pictures/competency-20.svg" alr="picture_of_time" />
          </div>
          <div class="needed_time">от 1ч</div>
          <div class="collumn">
            <div class="needed_time_terms">Настройка события GA<br />в интернет-магазине</div>
          </div>
        </div>

        <div class="skill_block col-sm-12 col-md-12 col-lg-4 col-xl-4 mx-sm-auto mx-md-auto">
          <div class="skill_img">
            <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
            <img src="pictures/competency-21.svg" alr="picture_of_time" />
          </div>
          <div class="needed_time">от 20ч</div>
          <div class="collumn">
            <div class="needed_time_terms">Разработка мобильной<br />версии сайта</div>
          </div>
        </div>

        <div class="skill_block col-sm-12 col-md-12 col-lg-4 col-xl-4 mx-sm-auto mx-md-auto">
          <div class="skill_img">
            <div class="wht_img_bg">
                <img src="pictures/icon-bg.svg" alt="picture" width="115" height="70" />
              </div>
            <img src="pictures/competency-22.svg" alr="picture_of_time" />
          </div>
          <div class="needed_time">от 8ч</div>
          <div class="collumn">
            <div class="needed_time_terms">Интеграция модуля<br />оплаты</div>
          </div>
        </div>

      </div>
    </div>
  </div>

  <script>
    function showBlock() {
      let ab = document.getElementById("admin_block");
      ab.style.display = "block";
    }
    function hideBlock() {
      let ab = document.getElementById("admin_block");
      ab.style.display = "none";
    }
    function becomeDarker(bd) {
      bd.style.backgroundColor = "#d13018";
    }
    function becomeBrighter(bb) {
      bb.style.backgroundColor = "#f04d35";
    }
    function showBorder(sb) {
      sb.style.borderBottom = "3px solid #f14d34";
    }
    function hideBorder(hb) {
      hb.style.borderBottom = "none";
    }
  </script>
</body>

  
  
  -------------------------------------------------------------
  
  @font-face {
  font-family: 'Montserrat';
  src: url("fonts/Montserrat-Medium.ttf");
}
body {
  font-family: 'Montserrat';
}
header {
  position: relative;
  z-index: 1;
  height:600px;
}
#header_section {
  position: relative;
  z-index: 1;
  background: url(pictures/druplicon.svg) no-repeat left top;
  background-color: rgba(0,0,0,.8);
  padding-bottom: 60px;
}
#bg_video {
z-index: -3;
position: absolute;
top: 0;
right: 0;
left: 0;
width: 100%;
filter: blur(3px);  
}
#header_logo {
  margin-top: -23px;
  margin-left: -15px;
}
#header_links {
  position: relative;
  z-index: 4;
  height: 50px;
  padding-top: 30px;
}
#admin_block {
  position: absolute;
  z-index: 5;
  background-color: #f04d35;
  display: none;
  border: 1px solid rgba(0,0,0,.15);
}
#admin_inside {
  margin: 6px 0;
}
.admin_txt {
  padding: 3px 0;
}
.admin_clr {
  padding: 0 15px;
  color: #fff;
}
.admin_clr:hover {
  text-decoration: none;
  color: #fff;
}
#razr_block {
  padding: 70px 0 60px;
}
.tarifs_link {
  height: 360px;
}
#razr {
  font-size: 52px;
  line-height: 60px;
  font-weight: bold;
  font-family: inherit;
  color: #fff;
  height: 33.33%;
}
#uslugi {
  font-size: 18px;
  line-height: 1.6;
  color: #fff;
  height: 33.33%;
}
#btn_frst {
  font-weight: 500;
  font-size: 12px;
  text-transform: uppercase;
  line-height: 1;
  color: #fff;
  padding: 22px 20px;
  width: 100%;
  text-align: center;
  border: 2px solid #f14d34;
  border-radius: 5px;
  background: none;
  height: 33.33%;
}
.gs_tripple {
  height: 25%;
}
.gs_block {
  border-left: 3px solid #f14d34; 
}
#trophy{
  position: absolute;
  left: 65px;
  
}
.gs_up_first {
  font-size: 48px;
  font-weight: bold;
  color: #fff;
  margin-top: -22px;
}
.gs_up_second {
  font-size: 24px;
  font-weight: bold;
  color: #fff;
}
.gs_down {
  font-size: 12px;
  line-height: 1.25;
  color: #fff;
}
#wht {
  position: relative;
  z-index: 1;
  background-color: #fff;
  height: 1500px;
}
#wht_block {
  padding:150px 0;
}
#wht_txt_up {
  font-weight: bold;
  font-size: 42px;
  color: #050c33;
  line-height: 1;
}
#wht_txt_down {
  font-weight: 500;
  font-size: 16px;
  color: #4f5a73;
  line-height: 1.25;
}
.wht_square{
  width: 25%;
  margin-bottom: 30px;
}
.wht_imgs {
  margin: 0 auto;
  font-weight: 500;
  font-size: 16px;
  color: #4f5a73;
  line-height: 1.42;
}
.wht_img_txt {padding: 0;}
.wht_square{padding:0;}

.wht_img_size {
  width: auto;
  margin: 0 0 40px 0;
}
.wht_img_bg {
  position: absolute;
  margin-left: -54px;
  margin-top: 20px;
}
.txt_top {
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  color: #fff;
}
#pointless_wht {
  height:500px;
  background-color: #fff;
}
#blk_cross {
  position: relative;
  z-index: 1;
  height:980px;
  background: linear-gradient(254.72deg,rgba(255,255,255,.276) -114.85%,rgba(255,255,255,0) 69.04%),#040613; 
}
#blk_back {
  position: relative;
  z-index: 2;
  background: url(pictures/drupal-logo-2.svg) no-repeat right bottom; 
}
#blk_txt {
  color: #050c33;
  text-align: center;
  font-weight: bold;
  font-size: 52px;
  line-height: 1;
  margin-top: -500px;
  margin-bottom: 60px;
  position: relative;
  z-index: 3;
}
.blk_img {
  background-color:#fff;
  height: 300px;
  width: 250px;
  position: relative;
  z-index: 3;
  border-radius: 5px;
  box-shadow: 20px 20px 40px rgba(5,12,51,.05);
}
#blk_cross {
  margin-top: -220px;
  position: relative;
  z-index: 1;
}
.blk_little_block {
  position: relative;
  z-index: 1;
  color: #fff;
  padding-top: 30%;
  padding-left:50%;
}
#laptop_img {
  margin-left: -15px;
  margin-top: -380px;
}
.blk_num {
  font-weight: bold;
  font-size: 12px;
  color: #828a9b;
  margin-bottom: 15px;
}

.blk_first_words {
  font-weight: bold;
  font-size: 18px;
  color: #050c33;
  line-height: 1.22;
  margin-bottom: 15px;
}
.btn {
  font-weight: 500;
  font-size: 16px;
  color: #4e5a73;
  line-height: 1.37;
}
.blk_corner_img {
  position: absolute;
  right: 0;
  bottom: 0;
  z-index: 3;
}
.blk_ecspertiza {
  font-weight: bold;
  font-size: 42px;
  margin-bottom: 65px;
  line-height: 1.1;
  margin-left: -35px;
}
.blk_ecsp_txt {
  border-left: 3px solid #f14d34;
  padding-left: 15px;
  padding-top: 5px;
  padding-bottom: 10px;
  min-height: 88px;
  height: 100%;
  font-weight: 500;
  font-size: 16px;
  color: rgba(256,256,256,.7);
  width: 260px;
  max-width: 100%;
}
.tarifs_block {
  height:500px;
  width:100%;
}
.blk_ecsp_txt a {
  color: #f14d34;
}
.tarif_col {
  padding: 60px 20px;
  background-color: #fff;
  border:3px solid #e6e6e6;
  border-radius: 5px;
}
.priced_type {
  margin-bottom: 50px;
  padding-bottom: 30px;
  border-bottom: 3px solid #e6e6e6;
  font-size: 22px;
  font-weight: bold;
  color: #f14d32;
  line-height: 1.3;
}
.tarif_goals {
  margin-bottom: 18px;
  line-height: 1.2;
  font-size: 16px;
  padding-left: 30px;
  color: #4e5972;
  font-weight: 500;
}
#tarifs_name {
  text-align: center;
  color: #000;
  font-weight: bold;
  font-size: 42px;
}
#tarifs_bg {
  height: 900px;
  background: url(pictures/D-background-opacity.svg) no-repeat right top;
}
#tarifs_blocks {
  padding-top: 160px;
}
.tarifs_btn {
  color: #f14d34;
  padding: 20px 10px;
  background: #fff;
  border: 1px solid #f14d34;
  border-radius: 5px;
}
#not_agree_tarif {
  text-align: center;
  line-height: 1.3;
  font-weight: 500;
  color: #828a9b;
}
#not_agree_tarif_down {
  font-size: 12px;
  width: 259px;
}
#not_agree_tarif_down a{
  text-decoration: underline;
  color: #050c33;
}
#not_agree_tarif_phone {
  display: none;
}
#skill_time {
  margin-top: 190px;
}
#devs_time_skills {
  font-weight: bold;
  font-size: 42px;
  color: #050c33;
  line-height: 1.1;
  padding-bottom: 60px;
}
.needed_time {
  font-size: 32px;
  color: #050c33;
  font-weight: bold;
}
.needed_time_terms {
  font-weight: 500;
  font-size: 16px;
  color: #4f5a73;
  line-height: 1.4;
}

@media screen and (max-width: 785px){
  #header_links {display: none;}
  
  #header_section {padding: 0;}
  header {height: 830px;}
 
  #razr {
  font-size: 32px;
  line-height: 1.2;
  text-align: center;
  font-weight: bold;
  }

  #uslugi {
  font-size: 14px;
  text-align: center;
  margin: 0 auto;
  }

  #btn_block {
  margin: 0 auto;
  }
  
  .tarifs_link {
  height: 320px;
  margin-bottom: 30px;
  }

  .gs_tripple {
  margin: 0 auto;
  width: 50%;
  padding: 0;
  }

  .gs_up_first {
  height: 50px;
  margin: -35px 0 10px;
  padding: 0;
  }

  .gs_block {
  border-left: 3px solid #f14d34;
  padding-left: 15px;
  padding-top: 5px;
  padding-bottom: 10px;
  margin-bottom: 20px;
  height: 100%;
  }

  #trophy{
  position: absolute;
  left: 65px;
  top: -3px;
  }


  #wht_txt_up {
  font-size: 24px;
  line-height: 1.1;
  }
  
  #wht_txt_down {
  font-size: 16px;
  line-height: 1.43;
  }

  .wht_imgs {
  margin: 0;
  font-size: 14px;
  line-height: 1.43;
  padding: 0;
  }
  .wht_square {
  width: 50%;
  }
  .wht_img_size {
  width: 81px;
  margin: 0 auto 40px;
  }

  .wht_img_txt {
  padding-left: 8%;
  }
  
  #blk_txt {
  text-align: center;
  font-size: 24px;
  line-height: 1.1;
  margin-top: -150px;
  margin-bottom: 60px;
  }
  
  .blk_img {
  background-color:#fff;
  height: 220px;
  width: 410px;
  margin-bottom: 5px;
  }

  .blk_ecspertiza {
  font-size: 24px;
  margin-bottom: 20px;
  margin-left: 0;
  padding-top: 250px;
  }

  .blk_little_block {
  padding-top: 0;
  padding-left:0;
  }
 
  #laptop_img {
  height: 360px;
  width: 370px;
  margin-top: 0;
  }

  .blk_ecsp_txt {
  min-height: 88px;
  height: 100%;
  width: 270px;
  margin-bottom: 30px;
  margin-left: 20px;
  }
  
  #tarifs_name {
  margin-top: 100px;
  }
  
  #tarifs_bg {
  height: 2250px;
  background: url(pictures/D-background-opacity.svg) no-repeat right top;
  background-size: auto, auto;
  }
  
  .tarif_col_big {margin-bottom: 10px;}

  #not_agree_tarif_phone {
  display: block;
  text-align: center;
  line-height: 1.3;
  font-weight: 500;
  color: #828a9b;
  }

  #not_agree_tarif {display: none;}

  #devs_time_skills {
  font-size: 24px;
  }

  .needed_time {
  text-align: center;
  }

  .needed_time_terms { 
  width: 60%;
  margin: 0 auto;
  }
 
  .skill_img {
  height: 81px;
  width: 81px;
  margin: 0 auto;
  }
  
  .skill_block {
  margin-bottom: 40px;
  }
}
