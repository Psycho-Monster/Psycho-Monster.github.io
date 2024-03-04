---
title: 微信小程序 禁止ios橡皮筋回弹
catalog: true
header-img: /img/header_img/lml_bg.jpg
---

https://blog.csdn.net/m0_61702149/article/details/126547969

## pages.json

![image-20230412151649240](/Users/feiji/Library/Application Support/typora-user-images/image-20230412151649240.png)

```js
disableScroll: true
```

## scroll-view

![image-20230412151701311](/Users/feiji/Library/Application Support/typora-user-images/image-20230412151701311.png)

```js
:enhanced="true"
:bounces="false"
```

