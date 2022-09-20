[![Portfolio](./favicon.ico)](https://github.com/Sjinwon/PORTFOLIO-2022)

# Portfolio
### 제작기간 : 7일
### 사용언어 : html css javascript photoshop

<br>

## ✔ 디자인 컨셉
Black & White, 미니멀리즘으로 화려한 포트폴리오 보다는 작품이 돋보일 수 있도록 했고, 작품 영역은 `가로스크롤` 을 사용해 사용자가 작품에 집중할 수 있도록 제작했다.

<br>

## ✔ 검색 최적화를 위한 오픈그래프(The Open Graph protocol)
웹 페이지가 소셜 미디어(페이스북 등)에 공유될 때 우선적으로 활용되는 정보를 지정한다.

``` html
  <meta property="og:type" content="website" />
  <meta property="og:title" content="jinwon's portfolio" />  
  <meta property="og:url" content="https://sjinwon.github.io/PORTFOLIO-2022/" />
  <meta property="og:image" content="./images/portfolio_seo.jpg" />
  <meta property="og:description" content="안녕하세요. 퍼블리셔 진원입니다." />
```

<br>

## ✔ SEO (검색 엔진 최적화, Search Engine Optimization)
구글이나 네이버 등에 자신의 웹 사이트/페이지를 노출할 수 있도록 정보를 최적화하는 작업을 말한다.

``` html
  <meta name="description" content="안녕하세요. 퍼블리셔 진원입니다." />
  <meta name="keywords" content="포트폴리오, portfolio, 퍼블리셔, 포폴" />
  <meta name="author" content="jinown" />
```


<br>

## ✔ fonts
페이지에서 사용할 "SUIT", "Lora" 폰트를 지정한다.

``` css
@font-face {
  font-family: "SUIT-Regular"; /* 본문 */
  src: url(../fonts/SUIT-Regular.woff);
}
@font-face {
  font-family: "SUIT-Medium";
  src: url(../fonts/SUIT-Medium.woff);
}
@font-face {
  font-family: "SUIT-Bold";
  src: url(../fonts/SUIT-Bold.woff);
}
@font-face {
  font-family: "Lora-Bold";
  src: url(../fonts/Lora-Bold.woff);
}
@font-face {
  font-family: "Lora-BoldItalic"; /* main title fonts */
  src: url(../fonts/Lora-BoldItalic.woff);
}
```
