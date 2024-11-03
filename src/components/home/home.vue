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
            <div class="main_news_navigation_text">
              <h1>Все новости</h1>
            </div>
          </a>
          <a href="#">
            <div class="main_news_navigation_text">
              <h1>Происшествия</h1>
            </div>
          </a>
          <a href="#">
            <div class="main_news_navigation_text">
              <h1>Спорт</h1>
            </div>
          </a>
          <a href="#">
            <div class="main_news_navigation_text">
              <h1>Политика</h1>
            </div>
          </a>
          <a href="#">
            <div class="main_news_navigation_text">
              <h1>Экономика</h1>
            </div>
          </a>
          <a href="#">
            <div class="main_news_navigation_text">
              <h1>Культура</h1>
            </div>
          </a>
        </div>
      </section>
    </main>
  </div>
</template>