<template>
  <footer class="footer">
    <nav>
      <ul class="row valign-wrapper">
        <div class="container">
        <li>
          <router-link class="router-link" to="/">
            トップ
          </router-link>
        </li>
        <li>
          <router-link class="router-link" to="/staffs">
            スタッフ紹介
          </router-link>
        </li>
        <li>
          <a class="router-link" href="https://activo.jp/articles/72556?via=user105899">
            メンバー募集
          </a>
        </li>
        <li>
          <a class="router-link" href="https://coderdojo-tachikawa.connpass.com/">
            次回の開催予定
          </a>
        </li>
        <li>
          <router-link class="router-link" to="/events">
            開催報告
          </router-link>
        </li>
        <li>
          <router-link class="router-link" to="/support">
            ご支援のお願い
          </router-link>
        </li>
        <li>
          <router-link class="router-link" to="/contact">
            お問い合わせ
          </router-link>
        </li>
        <li>
          <a href="https://lin.ee/vhWQhPP">
            <img class="valign-wrapper line-img" src="https://scdn.line-apps.com/n/line_add_friends/btn/ja.png" alt="友だち追加" height="36" border="0">
          </a>
        </li>
        </div>
      </ul>
      <div class="row s6 valign-wrapper">
        <img class="circle left square-icon" alt="corder dojo tachikawa" src="../assets/dojo-logo.jpg" />
        <h6 class='copyright'>©2021 Corder Dojo Tachikawa</h6>
      </div>
    </nav>
  </footer>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer {
  font-size: 18px;
  height: initial;
}
nav {
  background: initial;
  box-shadow: initial;
  color: #0F0F0F;;
  display: flex;
  flex-direction: column;
  height: initial;
  justify-content: center;
}
@media screen and (min-width: 1020px) and (max-width: 1275px) {
  nav {
    display: flex;
  }
}
@media screen and (min-width: 620px) and (max-width: 1020px) {
  nav {
    display: block;
  }
}
h1 {
  font-size: initial;
  line-height: initial;
  margin: initial;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  white-space: nowrap;
}
a {
  color: #42b983;
}
.footer {
  background: url('../assets/back_01.png') repeat center center;
  background-color: #fff;
  color: #0F0F0F;
  margin-bottom: initial;
  z-index: 100;
  box-shadow: 0 -3px -1px 2px rgba(0,0,0,0.12);
}
.inner-icon {
  margin: 12px;
}
.line-img {
  height: 32px;
  margin: 12px 10px;
}
.router-link {
  color: #000;
}
.square-icon {
  height: 36px;
  width: 36px;
}
.copyright {
  font-size: 1em;
}

.container{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
</style>
