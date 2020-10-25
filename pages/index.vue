<template>
  <div class="l_layout">
    <header class="l_header">
      <nav class="g_nav">
        <h1 class="title_header">
          <a href="/" class="title_header_link">ブランドサイトサンプル4</a>
        </h1>
        <ul class="g_nav_ul">
          <li class="g_nav_list">
            <a href="/" class="g_nav_link">HOME</a>
          </li>
          <li class="g_nav_list">
            <a href="/about" class="g_nav_link">ABOUT</a>
          </li>
          <li class="g_nav_list">
            <a href="/info" class="g_nav_link">INFO</a>
          </li>
          <li class="g_nav_list">
            <a href="/access" class="g_nav_link">ACCESS</a>
          </li>
          <li class="g_nav_list">
            <a href="/contact" class="g_nav_link">CONTACT</a>
          </li>
        </ul>
      </nav>
      <!-- ここがズレている原因 -->
      <div class="hero_header" :style="{height: height + 'px'}">
        <!-- <h1 class="hero_header_copy">ここにキャッチコピーが入ります</h1> -->
        <div class="hero_header_gray"></div>
      </div>
    </header>
    <main class="container">

    </main>
    <footer class="">
      <div class="footer_top">
        <div class="footer_area">

        </div>
      </div>
      <div class="footer_bottom">
        <small class="copyright">@2020 ブランドサイト制作サービス「Ratpost_branding」</small>
      </div>
    </footer>
  </div>
</template>
<style scoped>
/* html {
  display: block;
  width: 100%;
  word-break: break-all;
} */
.l_layout {

  word-break: break-all;
  overflow: hidden;
}
.title_header,
.g_nav_ul {
  font-size: 1.6em;
}
.l_header {
  width: 100%;
}
.g_nav {
  display: flex;
  justify-content: space-around;
  position: fixed;
  background-color: rgba(0,0,0,.5);
  color: #ffffff;
  width: 100%;
}
.title_header {
  padding: 24px 0;
}
.title_header_link {
  color: #ffffff;
  text-decoration: none;
}
.g_nav_ul {
  display: flex;
  justify-content: space-around;
  list-style: none;
  padding: 0;
  width: 50%;
  word-break: break-word;
}
.g_nav_list {
    display: block;
    margin: 0 8px;
    width: 100%;
    text-align: center;
    transition: .5s;
}
.g_nav_list:hover {
  background-color: #ffffff;
  opacity: .8;
}
.g_nav_link {
  color: #ffffff;
  display: block;
  padding: 24px 0;
  text-decoration: none;
  width: 100%;
}
.g_nav_link:hover {
  color: rgba(0,0,0,.5);
}
.hero_header {
  background-image: url(/hero_header.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  display: block;
  height: 100vh;
  width: 100%;
}
/* .hero_header_copy {
  color: #ffffff;
  position: absolute;
  top: 50%;
  left: 50%;
} */
.hero_header_gray {
  background-color: rgba(0,0,0,.2);
  height: 100%;
  width: 100%;
}
.footer_bottom {
  background-color: rgba(0,0,0,.5);
  color: #ffffff;
  text-align: center;
}
@media screen and (max-width: 768px) {
  .title_header {
    text-align: center;
    width: 100%;
  }
  .g_nav {
    flex-direction: column;
  }
  .g_nav_ul {
    flex-direction: column;
    margin: 0 auto;
    width: 100%;
  }
  .g_nav_list {
    margin: 0;
  }
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
})
</script>
