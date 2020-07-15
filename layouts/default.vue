<template>
  <html>
    <body id="top">
      <div class="wrap">

        <!-- Page Header -->
        <header class="h-header">
          <h1 class="h-logo">
            <a href="https://www.jenerate.co.jp">
              <img class="h-logo__img1" src="logo1.png">
              <img class="h-logo__img2" src="logo2.png">
            </a>
          </h1>
          <ul class="h-gNav__nav2--en">
            <li>
              <a href="https://www.jenerate.co.jp/">JP</a>
            </li>
            <li>
              <a class="current">EN</a>
            </li>
          </ul>
          <nav class="h-gNav">
            <ul class="h-gNav__nav1">
              <li id="menu-item-50" class="menu-item menu-item-type-post_type menu-item-object-page current-menu-item page_item page-item-11 current_page_item menu-item-50">
                <router-link to="">私たちについて</router-link>
              </li>
              <li id="menu-item-47" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-47">
                <router-link to="/business">事業案内</router-link>
              </li>
              <li id="menu-item-48" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-48">
                <a href="https://www.jenerate.co.jp/companyprofile/">会社情報</a>
              </li>
              <li id="menu-item-526" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-526">
                <a href="https://www.jenerate.co.jp/recruit/">採用情報</a>
              </li>
              <li id="menu-item-527" class="is-hide0805 menu-item menu-item-type-post_type_archive menu-item-object-report menu-item-527">
                <a href="https://www.jenerate.co.jp/report/">レポート</a>
              </li>
            </ul>
            <ul class="h-gNav__nav2">
              <li>
                <a href="https://www.jenerate.co.jp/">JP</a>
              </li>
              <li>
                <a href="https://www.jenerate.co.jp/english" class="current">EN</a>
              </li>
            </ul>
            <a class="c-btn4" href="https://www.jenerate.co.jp/contactus/">
              <span>CONTACT</span>
            </a>
            <div class="h-menu">
              <img class="h-menu-bk" src="menu1-bk.png" alt>
            </div>
          </nav>
        </header>
      <nuxt/>

        <!-- Footer -->
        <footer class="f-footer">
          <div class="l-inner2">
            <div class="f-main">
              <div class="f-block1">
                <a class="f-logo1">
                  <img src="logo1.png">
                </a>
                <p class="f-lead1">
                  あらゆる手段を駆使して困難の多い0→1に挑みます。
                </p>
                <div class="f-block2">
                  <div>
                    <p>
                      東京都渋谷区
                      <br class="is-sp">
                        恵比寿南3-1-19恵比寿ライトビル4F
                    </p>
                    <p class="f-tel">
                      TEL:03-4405-6844
                    </p>
                  </div>
                  <a class="c-btn2" href="">
                    <span>CONTACT</span>
                  </a>
                </div>
              </div>
              <nav class="f-nav">
                <div>
                  <dl>
                    <dt>
                      私たちについて
                    </dt>
                  </dl>
                  <dl class="js-btn">
                    <dt>
                      事業案内
                    </dt>
                    <dd>ジャパンエントリー</dd>
                    <dd>新規事業コンサルティング</dd>
                    <dd>イベントベストメント</dd>
                    <dd>実績</dd>
                  </dl>
                  <dl>
                    <dt>
                      会社情報
                    </dt>
                  </dl>
                </div>
                <div>
                  <dl class="js-btn is-hide1">
                    <dt>
                      採用情報
                    </dt>
                    <dd>キャリアパス</dd>
                    <dd>働く環境</dd>
                    <dd>募集要項</dd>
                    <dd>メンバーインタビュー</dd>
                  </dl>
                  <dl class="js-btn is-hide0805">
                    <dt>
                      レポート
                    </dt>
                    <dd>事例</dd>
                    <dd>トレンド</dd>
                  </dl>
                </div>
                <div>
                  <dl>
                    <dt>
                      お問い合わせ
                    </dt>
                  </dl>
                  <dl>
                    <dt>
                      プライバシーポリシー
                    </dt>
                  </dl>
                  <dl class="f-btn1">
                    <dt>
                      <a class="c-ico1">
                        JIX CAPITAL
                      </a>
                    </dt>
                  </dl>
                </div>
              </nav>
              <ul class="h-gNav__nav2 is-hide2">
                <li>
                  <a class="current" href>JP</a>
                </li>
                <li>
                  <a href>EN</a>
                </li>
              </ul>
            </div>
            <p class="f-copyright">© 2019 Jenerate Partners Inc.</p>
          </div>
        </footer>
      </div>
    </body>
  </html>
</template>

<script>
export default {
}
</script>

<style>
</style>
