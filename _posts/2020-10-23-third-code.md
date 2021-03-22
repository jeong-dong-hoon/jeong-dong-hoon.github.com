---
layout: post
title:  "HTML5 세번째 날"
date:   2020-10-23 09:00:00 +0900
categories: HTML
---
## 학원 세번째 수업
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<style>
  body,
  html {
    margin: 0;
    height: 100%;
    width: 100%;
    background-color: #ccc;
    text-align: center;
    color: white;
  }

  header {
    margin: 1%;
    height: 10%;
    background-color: slategrey;
  }

  nav {
    margin: 1%;
    height: 10%;
    background-color: slategrey
  }

  section {
    height: 48.9%;
    width: 100%;
    background-color: slategrey;
  }

  section.bottom {
    margin-top: 1%;
    padding: 0;
    position: relative;
  }

  article {
    height: 40%;
    width: 100%;
    background-color: slategrey;
    float: right;
  }

  aside {
    margin-top: 4%;
    height: 58%;
    width: 100%;
    float: right;
    background-color: slategrey;
  }

  .container {
    /* border: black solid; */
    height: 70%;
    width: 80%;
    padding: 0;
    margin: 1%;
  }

  .asides {
    padding: 0;
    /* border: black solid; */
    margin-right: 1%;
    width: 17%;
    height: 70%;
    float: right;
  }

  .clearfix {
    clear: both;
  }

  footer {
    height: 7%;
    margin: 0% 1% 1% 1%;
    background-color: slategrey;
  }

  section>header {
    height: 15%;
    background-color: steelblue;
  }

  section>footer {
    position: absolute;
    bottom: 0;
    width: 98%;
    height: 15%;
    margin-top: 2%;
    margin-bottom: 0%;
    background-color: steelblue;
  }

  /* position :absolute,fixed는 float속성이있음 
부모요소에 display:static이 아닌 요소를 기준으로 위치를 잡음 
부모요소에 position:relative가들어가서 기준위치를 설정함*/
</style>

<body>
  <header>header</header>
  <nav>nav</nav>
  <div class="asides">
    <article>
      <figure>article
      </figure>
    </article>
    <aside>aside</aside>
  </div>
  <div class="container">
    <section>section</section>
    <section class="bottom">section
      <header>header</header>
      <footer>footer</footer>
    </section>
  </div>
  <div class="clearfix"></div>
  <footer>footer</footer>
</body>

</html>
```
HTML5 시맨틱(Semantic)태그에 대해배움