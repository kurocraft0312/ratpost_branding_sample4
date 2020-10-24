<template>
  <div>
    <header class="l_header">
      <nav class="g_nav">
        <ul class="g_nav_ul">
          <li class="g_nav_list"><a href="#" class="g_nav_link">HOME</a></li>
          <li class="g_nav_list"><a href="#" class="g_nav_link">ABOUT</a></li>
          <li class="g_nav_list"><a href="#" class="g_nav_link">INFO</a></li>
          <li class="g_nav_list"><a href="#" class="g_nav_link">ACCESS</a></li>
          <li class="g_nav_list"><a href="#" class="g_nav_link">CONTACT</a></li>
        </ul>
      </nav>
    </header>
    <main class="">

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
.g_nav_ul {
  display: flex;
  justify-content: space-around;
  background-color: rgba(0,0,0,.5);
  color: #ffffff;
  list-style: none;
  padding: 0;
}
.g_nav_list {
    display: block;
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
  text-decoration: none;
  width: 100%;
}
.g_nav_link:hover {
  color: rgba(0,0,0,.5);
}
.footer_bottom {
  background-color: rgba(0,0,0,.5);
  color: #ffffff;
  text-align: center;
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({

})
</script>
