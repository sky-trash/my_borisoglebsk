<script>
import '../../assets/style/root/root.scss'
import '../../assets/style/home/home.scss'
import Header from '../views/header.vue'

</script>
<template>
  <Header />
  <div class="container">
    <main class="main">
      <section class="main_search">
        <div class="main_search_icons">
          <img src="../../assets/icons/home/searth/search-base.svg" alt="">
        </div>
        <div class="main_search_text-news">
          <h1>Только оперативные новости</h1>
        </div>
        <div class="main_search_scan">
          <div class="main_search_scan-text">
            <h1>Поиск по сайту: новости, события и многое другое</h1>
          </div>
          <div class="main_search_scan-input">
            <input placeholder="Начните поиск по сайту..." type="search">
          </div>
        </div>
      </section>
      <section class="main_news">
        <div class="main_news_navigation">
          <a href="#">
            <div id="button-news" class="main_news_navigation_text">
              <h1>Все новости</h1>
            </div>
          </a>
          <a href="#">
            <div id="button-trips" class="main_news_navigation_text">
              <h1>Происшествия</h1>
            </div>
          </a>
          <a href="#">
            <div id="button-sport" class="main_news_navigation_text">
              <h1>Спорт</h1>
            </div>
          </a>
          <a href="#">
            <div id="button-policy" class="main_news_navigation_text">
              <h1>Политика</h1>
            </div>
          </a>
          <a href="#">
            <div id="button-economy" class="main_news_navigation_text">
              <h1>Экономика</h1>
            </div>
          </a>
          <a href="#">
            <div id="button-culture" class="main_news_navigation_text">
              <h1>Культура</h1>
            </div>
          </a>
          <a href="#">
            <div class="main_news_more">
              <div class="main_news_more_text">
                <h1>Подробнее</h1>
              </div>
              <div class="main_news_more_icons">
                <img src="../../assets/icons/home/searth/right.svg" alt="">
              </div>
            </div>
          </a>
        </div>
        <div class="main_news_content">
          <div class="main_news_content_tidings">
            <div class="main_news_content_tidings_card">
              <div class="main_news_content_tidings_card_icons">
                <img src="../../assets/icons/home/news/incidents.svg" alt="">
              </div>
              <div class="main_news_content_tidings_card_tags">
                <h1>Происшествия</h1>
              </div>
              <div class="main_news_content_tidings_card_text">
                <h1>В Воронежкой области потерпел крушение самолет Су-34</h1>
              </div>
              <div class="main_news_content_tidings_card_views">
                <div class="main_news_content_tidings_card_views_time">
                  <h1>Вчера, 23:56</h1>
                </div>
                <div class="main_news_content_tidings_card_views_scan">
                  <img src="../../assets/icons/home/time.svg" alt="">
                  <h1>546</h1>
                </div>
              </div>
            </div>
            <div class="main_news_content_tidings_card">
              <div class="main_news_content_tidings_card_icons">
                <img src="../../assets/icons/home/news/story.svg" alt="">
              </div>
              <div class="main_news_content_tidings_card_tags">
                <h1>История одного города</h1>
              </div>
              <div class="main_news_content_tidings_card_text">
                <h1>История <br>Теллермановского леса. Часть 1</h1>
              </div>
              <div class="main_news_content_tidings_card_views">
                <div class="main_news_content_tidings_card_views_time">
                  <h1>19 сентября, 16:00</h1>
                </div>
                <div class="main_news_content_tidings_card_views_scan">
                  <img src="../../assets/icons/home/time.svg" alt="">
                  <h1>2310</h1>
                </div>
              </div>
            </div>
            <div class="main_news_content_tidings_card">
              <div class="main_news_content_tidings_card_icons">
                <img src="../../assets/icons/home/news/story.svg" alt="">
              </div>
              <div class="main_news_content_tidings_card_tags">
                <h1>Истоия одного города</h1>
              </div>
              <div class="main_news_content_tidings_card_text">
                <h1>История <br>Теллермановского леса. Часть 2</h1>
              </div>
              <div class="main_news_content_tidings_card_views">
                <div class="main_news_content_tidings_card_views_time">
                  <h1>19 сентября, 16:00</h1>
                </div>
                <div class="main_news_content_tidings_card_views_scan">
                  <img src="../../assets/icons/home/time.svg" alt="">
                  <h1>2310</h1>
                </div>
              </div>
            </div>
            <div class="main_news_content_tidings_card">
              <div class="main_news_content_tidings_card_icons">
                <img src="../../assets/icons/home/news/sport.svg" alt="">
              </div>
              <div class="main_news_content_tidings_card_tags">
                <h1>Спорт</h1>
              </div>
              <div class="main_news_content_tidings_card_text">
                <h1>Нападающий ФК «Кристалл-МЭ3» о матче <br>с главными соперниками</h1>
              </div>
              <div class="main_news_content_tidings_card_views">
                <div class="main_news_content_tidings_card_views_time">
                  <h1>Вчера, 23:56</h1>
                </div>
                <div class="main_news_content_tidings_card_views_scan">
                  <img src="../../assets/icons/home/time.svg" alt="">
                  <h1>546</h1>
                </div>
              </div>
            </div>
          </div>
          <div class="main_news_content_advertising">
            <div class="main_news_content_advertising_card">
              <h1>Рекламный баннер</h1>
            </div>
            <div class="main_news_content_advertising_card">
              <h1>Рекламный баннер</h1>
            </div>
            <div class="main_news_content_advertising_card">
              <h1>Рекламный баннер</h1>
            </div>
          </div>
        </div>
      </section>
      <section class="main_reasons">
        <div class="main_reasons_background">
          <img id="reasons" src="../../assets/icons/home/reasons/reasons.svg" alt="">
          <div class="main_reasons_background_text">
            <div class="main_reasons_bacfground_text_logo">
              <h1>5 весомых причин <br>перееxать в Борисоглебск</h1>
            </div>
            <div class="main_reasons_background_text_row">
              <div class="main_reasons_background_text_row_card">
                <img src="../../assets/icons/home/reasons/story.svg" alt="">
                <h1>Исторический город</h1>
              </div>
              <div class="main_reasons_background_text_row_card">
                <img src="../../assets/icons/home/reasons/work.svg" alt="">
                <h1>Возможность трудоустройства</h1>
              </div>
              <div class="main_reasons_background_text_row_card">
                <img src="../../assets/icons/home/reasons/life.svg" alt="">
                <h1>Жилье</h1>
              </div>
              <div class="main_reasons_background_text_row_card">
                <img src="../../assets/icons/home/reasons/rest.svg" alt="">
                <h1>Возможности для отдыха</h1>
              </div>
              <div class="main_reasons_background_text_row_card">
                <img src="../../assets/icons/home/reasons/children.svg" alt="">
                <h1>Объекты для детей</h1>
              </div>
            </div>
            <div class="main_reasons_background_text_button">
              <a href="#">
                <button>
                  <h1>Подробнее</h1>
                  <img src="../../assets/icons/home/reasons/right.svg" alt="">
                </button>
              </a>
            </div>
          </div>
        </div>
      </section>
      <section class="main_advertising">
        <div class="main_advertising_block">
          <h1>Рекламный баннер</h1>
        </div>
      </section>
      <section class="main_car">
        <div class="main_car_text">
          <h1>Саратов</h1>
          <p>3 часа 15 минут</p>
          <h1>Борисоглебск</h1>
        </div>
        <div class="main_car_icons">
          <img src="../../assets/icons/home/" alt="">
        </div>
      </section>
    </main>
  </div>
</template>