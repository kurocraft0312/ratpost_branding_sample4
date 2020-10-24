<template>
  <div>
    <header class="">
      <nav class="g_nav">
        <ul class="g_nav_ul">
          <li><a href="#" class="g_nav_link">HOME</a></li>
          <li><a href="#" class="g_nav_link">ABOUT</a></li>
          <li><a href="#" class="g_nav_link">INFO</a></li>
          <li><a href="#" class="g_nav_link">ACCESS</a></li>
          <li><a href="#" class="g_nav_link">CONTACT</a></li>
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
  list-style: none;
}
.g_nav_link {
  text-decoration: none;
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
