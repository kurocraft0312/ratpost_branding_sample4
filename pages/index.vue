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
      <div class="hero_header">
        <h2 class="hero_header_copy">ここにキャッチコピーが入ります</h2>
        <div class="hero_header_gray"></div>
      </div>
    </header>
    <main class="container">
      <div class="bodycopy">
        <h2 class="bodycopy_title">Lorem ipsum dolor sit amet.</h2>
        <p class="bodycopy_contents">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum maiores quam exercitationem mollitia optio explicabo error esse harum, molestias non pariatur consequatur at repudiandae, cum saepe illum dolor reiciendis nostrum?</p>
        <div class="bodycopy_about">
          <img src="cap1.jpg" alt="起業支援" class="bodycopy_img">
          <img src="cap2.jpg" alt="経営コンサルティング" class="bodycopy_img">
          <img src="cap3.jpg" alt="競合リサーチ" class="bodycopy_img">
        </div>
      </div>
      <div class="newinfo_group">
        <div class="newinfo">
          <div class="newinfo_contents">
            <time>2020.04.21</time>
          </div>
          <div class="newinfo_cat">お知らせ</div>
          <div class="newinfo_body">
            <p>
              <a href="#" class="newinfo_link">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam, voluptate?</a>
            </p>
          </div>
        </div>
        <div class="newinfo">
          <div class="newinfo_contents">
            <time>2020.04.21</time>
          </div>
          <div class="newinfo_cat">お知らせ</div>
          <div class="newinfo_body">
            <p>
              <a href="#" class="newinfo_link">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam, voluptate?</a>
            </p>
          </div>
        </div>
        <div class="newinfo">
          <div class="newinfo_contents">
            <time>2020.04.21</time>
          </div>
          <div class="newinfo_cat">お知らせ</div>
          <div class="newinfo_body">
            <p>
              <a href="#" class="newinfo_link">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam, voluptate?</a>
            </p>
          </div>
        </div>
        <div class="newinfo">
          <div class="newinfo_contents">
            <time>2020.04.21</time>
          </div>
          <div class="newinfo_cat">お知らせ</div>
          <div class="newinfo_body">
            <p>
              <a href="#" class="newinfo_link">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam, voluptate?</a>
            </p>
          </div>
        </div>
        <div class="newinfo">
          <div class="newinfo_contents">
            <time>2020.04.21</time>
          </div>
          <div class="newinfo_cat">お知らせ</div>
          <div class="newinfo_body">
            <p>
              <a href="#" class="newinfo_link">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quam, voluptate?</a>
            </p>
          </div>
        </div>
      </div>
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
.l_layout {
  background-color: #011433;
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
  z-index: 1;
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
.hero_header_copy {
  color: #ffffff;
  font-size: 2.4rem;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateY(-50%) translateX(-50%);
}
.hero_header_gray {
  background-color: rgba(0,0,0,.2);
  height: 100%;
  width: 100%;
}
.container {
  margin: 0 auto;
  width: 80%;
}
.bodycopy {
  color: #ffffff;
  text-align: center;
}
.bodycopy_title {
  display: block;
  font-size: 2.4rem;
  margin: 64px auto;
}
.bodycopy_contents {
  font-size: 1.6rem;
  margin: 64px auto;
}
.bodycopy_about {
  display: flex;
  justify-content: space-around;
  margin: 64px auto;
}
.bodycopy_img {
  margin: auto 16px;
  opacity: .4;
  width: 100%;
}
.newinfo_group {
  color: #ffffff;
}
.newinfo {
  display: flex;
  justify-content: center;
}
.newinfo_cat {
  background-color: #ffffff;
  color: #011433;
  font-weight: bold;
  margin: 4px 8px;
  padding: 0 8px;
}
.newinfo_link {
  color: #ffffff;
  text-decoration: none;
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
  .bodycopy_about {
    flex-direction: column;
  }
  .bodycopy_img {
    margin: 16px auto;
  }
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
})
</script>
