<script>
import '../../assets/style/root/root.scss'
import '../../assets/style/views/header.scss'
</script>

<template>
  <div class="container">
    <header class="header">
      <section class="header-up">
        <div class="header-up_work">
          <a href="../directory/directory.vue">
            <h1>Работа в Борисоглебске</h1>
          </a>
        </div>
        <div class="header-up_life">
          <a href="../directory/directory.vue">
            <h1>Жилье в Борисоглебске</h1>
          </a>
        </div>
        <div class="header-up_contact">
          <a href="../contact/contact.vue">
            <h1>Наши контакты</h1>
          </a>
        </div>
        <div class="header-up_search">
          <a href="#">
            <div class="header-up_search_icons">
              <img src="../../assets/icons/header/search.svg" alt="">
            </div>
            <div class="header-up_search_text">
              <h1>Поиск по сайту</h1>
            </div>
          </a>
        </div>
        <div class="header-up_login">
          <a href="#">
            <div class="header-up_login_icons">
              <img src="../../assets/icons/header/login.svg" alt="">
            </div>
            <div class="header-up_login_text">
              <h1>Вход</h1>
            </div>
          </a>
        </div>
      </section>
      <section class="header-logo">
        <div class="header-logo_icons">
          <a class="../Index.vue">
            <img src="../../assets/icons/header/logo.svg" alt="">
          </a>
        </div>
      </section>
      <section class="header-down">
        <nav class="header-down_nav">
          <a href="#">
            <div class="header-down_nav_menu">
              <div class="header-down_nav_menu_icons">
                <img src="../../assets/icons/header/burger.svg" alt="">
              </div>
              <div class="header-down_nav_menu_text">
                <h1>Меню</h1>
              </div>
            </div>
          </a>
          <a href="#">
            <div class="header-down_nav_navigatin">
              <div class="header-down_nav_navigation_icons">
                <img src="../../assets/icons/header/active-elip.svg" alt="">
              </div>
              <div class="header-down_nav_navigation_text">
                <h1>Городские новости</h1>
              </div>
            </div>
          </a>
          <a href="#">
            <div class="header-down_nav_navigatin">
              <div class="header-down_nav_navigation_icons">
                <img src="../../assets/icons/header/active-elip.svg" alt="">
              </div>
              <div class="header-down_nav_navigation_text">
                <h1>Афиша</h1>
              </div>
            </div>
          </a>
          <a href="#">
            <div class="header-down_nav_navigatin">
              <div class="header-down_nav_navigation_icons">
                <img src="../../assets/icons/header/active-elip.svg" alt="">
              </div>
              <div class="header-down_nav_navigation_text">
                <h1>Родной город</h1>
              </div>
            </div>
          </a>
          <a href="#">
            <div class="header-down_nav_navigatin">
              <div class="header-down_nav_navigation_icons">
                <img src="../../assets/icons/header/active-elip.svg" alt="">
              </div>
              <div class="header-down_nav_navigation_text">
                <h1>Справочник</h1>
              </div>
            </div>
          </a>
          <a href="#">
            <div class="header-down_nav_navigatin">
              <div class="header-down_nav_navigation_icons">
                <img src="../../assets/icons/header/active-elip.svg" alt="">
              </div>
              <div class="header-down_nav_navigation_text">
                <h1>Достопримечательности</h1>
              </div>
            </div>
          </a>
        </nav>
      </section>
    </header>
  </div>
</template>