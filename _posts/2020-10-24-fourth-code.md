---
layout: post
title:  "HTML5 네번째 날"
date:   2020-10-24 09:00:00 +0900
categories: HTML
---
## 학원 네번째 수업
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
    .box {
      width: 300px;
      height: 300px;
      background-color: yellow;
      margin: auto;
      position: relative;
    }

    .box .item {
      width: 50px;
      height: 50px;
    }

    .box .item.item1 {width: 100%;
      height: 20%;
      background-color: red;
      /* margin-bottom: 5px; */
    }

    .box .item.item2 {
      width: 30%;
      height: 70%;
      position: absolute;
      left: 0;
      background-color: green;
      /* margin: 5px 0px; */
    }

    .box .item.item3 {
      width: 70%;
      height: 70%;
      position: absolute;
      right: 0;
      background-color: blue;
    }
    .box .item.item4 {width: 100%;
    height: 10%;
  position: absolute;
bottom: 0;
background-color: #ccc;}
  </style>
</head>

<body>
  <div class="box">
    <div class="item item1">item1</div>
    <div class="item item2">item2</div>
    <div class="item item3">item3</div>
    <div class="item item4">item4</div>
  </div>
</body>

</html>
```
선택자(selector)에대해 배움