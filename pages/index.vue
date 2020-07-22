<template>
  <html>
    <body id="top">
      <div class="wrap">

        <!-- Page Header -->

        <!-- Main Content -->
        <aside class="c-mv1">
          <div class="c-mv1__ttlBlock js-eff1">
            <h2 class="c-ttl2">
              <span class="js-eff1">私たちについて</span>
            </h2>
            <p class="c-ttl3">
              <span class="js-eff1">OUR STRENGTHS</span>
            </p>
          </div>
          <div class="c-mv1__imgBlock">
            <p class="js-eff1">
              <img src="img-1.jpg">
            </p>
          </div>
        </aside>

        <main>
          <section class="l-inner4 p-ourBlock1">
            <h3 class="c-ttl4-2">
              Zero to
              <strong>One</strong>
            </h3>
            <div class="c-lead1">
              <span class="js-eff1">
                  いま世界は、社会構造の変化や価値観の多様化など、かつてないほどのスピードで変化しています。<br>
                  社会が抱えるニーズや欲求、社会問題も一層複雑且つ解決が困難なものになっています。<br>
                  そして、ビジネスの成長と衰退のサイクルも加速度的に進み、従来の考え方やアプローチなど、今あることの延長線上に成長が描きにくい時代に突入しています。<br>
                  だからこそ、これまでの“当たり前”に疑問を投げかけ、本質的に価値のあること、意味のあることを愚直に追求し、刺激的な未来を創造していくことに意義があります。<br>
                  それは“0から1”という誰も踏み込んだことのない領域に果敢にチャレンジすることです。<br>
              </span>
            </div>
          </section>
          <section class="p-ourBlock2 u-mt100px u-pb100px u-mt3em--sp u-pb3em--sp">
            <p class="p-ourImg1 is-pc">
              <img src="img-3.jpg">
            </p>
            <p class="p-ourImg2 is-sp">
              <img src="pic-1.jpg">
            </p>
            <div class="u-posRelative">
              <div class="p-ourBlock3 u-sansSerif2">
                <p class="c-lead1">
                  Jenerate Partnersは、“Venture for Extraordinary”というスローガンに想いを込めて、特別な未来の実現に向けて、“0から1” に情熱を持った新規事業立ち上げのプロフェッショナルが集い、事業創造に果敢にチャレンジを続けながら「事業創造が活発な社会」の構築を目指しています。
                </p>
                <div class="u-mt70px u-mt2em--sp">
                  <a class="c-btn1 u-mr40px u-mr0px--sp u-mb1_5em" href="">
                    <span>事業案内</span>
                  </a>
                  <a class="c-btn1" href="">
                    <span>メンバー紹介</span>
                  </a>
                </div>
              </div>
            </div>
          </section>
          <nav class="c-breadcrumb l-inner2 u-mt2em u-mb2em">
            <span property="itemListElement" typeof="ListItem">
              <a property="item" class="home">
                <span property="name">ホーム</span>
              </a>
            </span>
            <span class="bcn-split">
            </span>
            <span class="post post-page current-item">
              私たちについて
            </span>
          </nav>
          <section　class="p-ourBlock4">
            <img class="is-pc"　src="img-4.jpg">
            <img class="is-sp" src="img-13.jpg">
          </section>
          <nav>
            <ul class="u-grid f-footrNav">
               <li class="u-col6 u-col12--sp is-hide1">
                  <a class="c-card3--b" href="https://www.jenerate.co.jp/recruit/">
                    <p class="c-card3__en">
                      CAREERS
                    </p>
                    <p class="c-card3__ttl">
                      VENTURE WITH US
                    </p>
                    <p class="c-card3__jp c-border1">
                      採用情報
                    </p>
                  </a>
               </li>
               <li class="u-col6 u-col12--sp">
                  <a class="c-card3" href="https://www.jenerate.co.jp/companyprofile/">
                    <p class="c-card3__en">
                      COMPANY
                    </p>
                    <p class="c-card3__ttl">
                      <img class="df" src="logo1.png" alt>
                      <img class="ov" src="logo2.png" alt>
                    </p>
                    <p class="c-card3__jp c-border1">
                      会社情報
                    </p>
                  </a>
               </li>
            </ul>
          </nav>
        </main>




      <!-- Footer -->

          </div>
        </footer>
      </div>
    </body>
  </html>
</template>

<script>
  export default {
    head(){
      return {
        title: "私たちについて",
        meta: [
          { hid: 'description', name: 'description', content: 'My custom description' }
        ]
      }
    }
  }
</script>

<style>


.p-ourBlock1 {
    margin-right: 0;
    padding-top: 16vw;
    position: relative;
    background-color: #fff;
}
@media screen and (min-width: 750px){
.p-ourBlock1 {
    margin-right: 16.66667vw;
    padding-top: 8.75vw;
}
}



.p-ourBlock1 .c-lead1 {
    margin: 3.47222vw 0;
}
@media screen and (min-width: 750px){
.p-ourBlock2 .c-lead1 {
    margin-top: 3.47222vw;
}
}



@media screen and (min-width: 750px){
.p-ourImg1 {
    position: absolute;
    top: 0;
    left: 0;
    padding-left: 8.33333vw;
}
}



.p-ourBlock2 {
    padding: 0;
}
@media screen and (min-width: 750px){
.p-ourBlock2 {
    position: relative;
    padding-left: 8.33333vw;
    padding-top: 10.41667vw;
}
}



.p-ourBlock3 {
    padding: 0 5.33333vw;
    margin-right: 0;
}
@media screen and (min-width: 750px){
.p-ourBlock3 {
    background-color: #fff;
    margin-top: 4.16667vw;
    margin-right: 32.63889vw;
    padding: .69444vw 6.94444vw 6.94444vw 0;
}
}



.u-pb0em--sp {
    padding-bottom: 0em !important;
}

.u-mr0px--sp {
    margin-right: 0px !important;
}



.u-mt2em {
    margin-top: 2em !important;
}
@media screen and (min-width: 750px){
.u-mt2em {
    margin-top: 2em !important;
}
}



.u-mb2em {
    margin-bottom: 2em !important;
}
@media screen and (min-width: 750px){
.u-mb2em {
    margin-bottom: 2em !important;
}
}


.u-mt2em--sp {
    margin-top: 2em !important;
}


.u-pb3em--sp {
    padding-bottom: 3em !important;
}
.u-mt3em--sp {
    margin-top: 3em !important;
}


.u-mb6em--sp {
    margin-bottom: 6em !important;
}


.u-col12--sp {
    width: 100% !important;
}


@media screen and (min-width: 750px){
.u-col6 {
    width: 50% !important;
}
}



.u-mb1_5em {
    margin-bottom: 1.5em !important;
}
@media screen and (min-width: 750px){
.u-mb1_5em {
    margin-bottom: 1.5em !important;
}
}


@media screen and (min-width: 750px){
.u-mt100px {
    margin-top: 100px !important;
}
}



@media screen and (min-width: 750px){
.u-pb100px {
    padding-bottom: 100px !important;
}
}



@media screen and (min-width: 750px){
.u-mt70px {
    margin-top: 70px !important;
}
}



@media screen and (min-width: 750px){
.u-mr40px {
    margin-right: 40px !important;
}
}



@media screen and (min-width: 750px){
.u-posRelative {
    position: relative !important;
}
}



.u-grid {
    display: flex;
    flex-wrap: wrap;
}


</style>
