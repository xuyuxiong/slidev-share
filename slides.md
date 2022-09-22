---
theme: penguin
---

# 动画库
<br>
<p class="center">今天给大家分享几个好用的JavaScript动画库</p>
<br>
<p class="right"> 分享人：徐誉雄 </p>

<style>
h1 {
  margin-top: 100px;
  text-align: center;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.center {
  text-align: center;
}
.right {
  padding-top: 50px;
  text-align: right;
}

</style>

---


# Animate.css

animate.css 是一个使用CSS3的 animation 制作的动画效果的CSS集合，里面预设了很多种常用的动画，且使用非常简单。

## 基本使用

<br>

```html
<h1 class="animate__animated animate__bounce">An animated element</h1>

<!-- 添加延迟 -->
<div class="animate__animated animate__bounce animate__delay-2s">Example</div>

<!-- 控制动画速度 -->
<div class="animate__animated animate__bounce animate__faster">Example</div>

<!-- 控制动画重复次数 -->
<div class="animate__animated animate__bounce animate__repeat-2">Example</div>
```
<br>

Read more about [Animate.css?](https://animate.style/)

<style>
h1, h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
h2 {
  font-size: 1.4rem !important;
}
</style>

---

# Anime.js

 Anime.js 是一个轻量的JavaScript 动画库， 拥有简单而强大的API。可对 CSS 属性、 SVG、 DOM 和JavaScript 对象进行动画。轻便，gzip压缩完只有9kb左右。 

<br>

## 特性

<br>

- 🌈 **CSS PROPERTIES** - 任何 CSS 属性都可以设置动画。
- 🧱 **CSS TRANSFORMS** - Animate CSS 会单独设置tranform属性，可以为每个transform属性指定不同的时间。
- 🧑‍💻 **OBJECT PROPERTIES** - 任何包含数值的 Object 属性都可以进行动画处理。
- 🤹 **DOM ATTRIBUTES** - 任何包含数值的 DOM 属性都可以设置动画。
- 🎥 **SVG ATTRIBUTES** - 与任何其他DOM 属性一样，所有包含至少一个数值的 SVG 属性都可以设置动画。

<br>

Show usage [Documentation](https://alexfox.dev/lax.js/)   Read more about [Anime.js?](https://animejs.com/)


<style>
h1, h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
h2 {
  font-size: 1.4rem !important;
}
</style>

---

# Lax.js

一款原生零依赖的制作跟随页面滑动的 JavaScript 动画插件，这款插件非常的轻巧，压缩版大小只有3kb。当滑动页面时，帮助创建酷炫的动画效果，比如滚动视差、变形移动等基本的动画效果，响应式兼容方面，比如手机端也有不错的支持。除了可以使用插件默认集成的动画属性，还可以自定义更加丰富的动画属性。


![Lax.js](https://camo.githubusercontent.com/60dbe0b2a1475b0c5602d175855ba9fc8a71d8ed9aed2e0490b8f8d72770b09f/68747470733a2f2f692e696d6775722e636f6d2f584e7676414f762e676966)



Showcases [Example](https://alexfox.dev/lax.js/)     Read more about [Lax.js?](https://github.com/alexfoxy/lax.js)


<style>
h1, h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
h2 {
  font-size: 1.4rem !important;
}
</style>

---

# GreenSock

 一个JavaScript动画库，可轻松对HTML元素进行动画处理。用于创建高性能，零依赖性，跨浏览器动画，声称在超过 400 万个网站中使用。 

## 特点

<br>

- ✈️ **Fast** - 速度快，专门优化了动画性能，使之实现和css一样的高性能动画效果。
- 🌰 **Lightweight modularization** - 轻量与模块化。模块化与插件式的结构保持了核心引擎的轻量，TweenLite包非常小(基本上低于7kb)。提供了TweenLite, TimelineLite, TimelineMax 和 TweenMax不同功能的动画模块，你可以按需使用。
- 🍊 **No dependency** - 没有依赖
- 🤹 **Flexible control** - 灵活控制。不用受限于线性序列，可以重叠动画序列，可以通过精确时间控制，灵活地使用最少的代码实现动画。


Read more about [GreenSock?](https://greensock.com/)


<style>
h1, h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
h2 {
  font-size: 1.4rem !important;
}
</style>

---


# react-spring

 是一个基于弹簧物理学的动画库，满足大多数与UI相关的动画需求，提供了足够灵活的工具，可以自信地将想法投射到不断变化的界面中。该库代表了一种现代动画方法。它继承了 animated 强大的插值和性能，以及 react-motion 的易用性。

<br>

<img width="300" src="https://pic.imgdb.cn/item/632c385516f2c2beb1523114.gif" />

<!-- <img width="300" src="https://pic.imgdb.cn/item/632c395516f2c2beb1532c46.gif" /> -->

<br>

Read more about [react-spring?](https://react-spring.dev/)


<style>
h1, h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
h2 {
  font-size: 1.4rem !important;
}
</style>

