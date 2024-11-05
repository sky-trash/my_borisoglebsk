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
          <img src="../../assets/icons/home/search-base.svg" alt="">
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
            <img src="../../assets/icons/home/searсh-button.svg" alt="">
          </div>
        </div>
      </section>
      <section class="main_news">
        <div class="main_news_navigation">
          <a href="#">
            <div id="button-news"class="main_news_navigation_text">
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
            <div id="button-economy"class="main_news_navigation_text">
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
              <img src="../../assets/icons/home/right.svg" alt="">
            </div>
          </div>
        </a>
        </div>
        <div class="main_news_content">
          <div class="main_news_content_card">
            <div class="main_news_content_card_icons">
              <img src="../../assets/icons/home/incidents.svg" alt="">
            </div>
            <div class="main_news_content_card_tags">
              <h1>Происшествия</h1>
            </div>
            <div class="main_news_content_card_text">
              <h1>В Воронежкой области потерпел крушение самолет Су-34</h1>
            </div>
            <div class="main_news_content_card_views">
              <div class="main_news_content_card_views_time">
                <h1>Вчера, 23:56</h1>
              </div>
              <div class="main_news_content_card_views_scan">
                <img src="../../assets/icons/home/time.svg" alt="">
                <h1>546</h1>
              </div>
            </div>
          </div>
          <div class="main_news_content_card">
            <div class="main_news_content_card_icons">
              <img src="../../assets/icons/home/story.svg" alt="">
            </div>
            <div class="main_news_content_card_tags">
              <h1>История одного города</h1>
            </div>
            <div class="main_news_content_card_text">
              <h1>В Воронежкой области потерпел крушение самолет Су-34</h1>
            </div>
            <div class="main_news_content_card_views">
              <div class="main_news_content_card_views_time">
                <h1>Вчера, 23:56</h1>
              </div>
              <div class="main_news_content_card_views_scan">
                <img src="../../assets/icons/home/time.svg" alt="">
                <h1>546</h1>
              </div>
            </div>
          </div>
          <div class="main_news_content_card">
            <div class="main_news_content_card_icons">
              <img src="../../assets/icons/home/story.svg" alt="">
            </div>
            <div class="main_news_content_card_tags">
              <h1>Истоия одного города</h1>
            </div>
            <div class="main_news_content_card_text">
              <h1>В Воронежкой области потерпел крушение самолет Су-34</h1>
            </div>
            <div class="main_news_content_card_views">
              <div class="main_news_content_card_views_time">
                <h1>Вчера, 23:56</h1>
              </div>
              <div class="main_news_content_card_views_scan">
                <img src="../../assets/icons/home/time.svg" alt="">
                <h1>546</h1>
              </div>
            </div>
          </div>
          <div class="main_news_content_card">
            <div class="main_news_content_card_icons">
              <img src="../../assets/icons/home/sport.svg" alt="">
            </div>
            <div class="main_news_content_card_tags">
              <h1>Спорт</h1>
            </div>
            <div class="main_news_content_card_text">
              <h1>В Воронежкой области потерпел крушение самолет Су-34</h1>
            </div>
            <div class="main_news_content_card_views">
              <div class="main_news_content_card_views_time">
                <h1>Вчера, 23:56</h1>
              </div>
              <div class="main_news_content_card_views_scan">
                <img src="../../assets/icons/home/time.svg" alt="">
                <h1>546</h1>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>