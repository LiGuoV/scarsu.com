---
title: 360FED课程——HTML
categories: 
- html # 一级分类
tags: 
- 360fed
- html
date: 2018-09-02
description: 这么穷为什么还花钱买HTML学？
---
<!-- TOC -->

- [1. 前端做什么](#1-%E5%89%8D%E7%AB%AF%E5%81%9A%E4%BB%80%E4%B9%88)
- [2. 知识图谱/技术栈](#2-%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1%E6%8A%80%E6%9C%AF%E6%A0%88)
    - [2.1. 语言](#21-%E8%AF%AD%E8%A8%80)
    - [2.2. 行业标准](#22-%E8%A1%8C%E4%B8%9A%E6%A0%87%E5%87%86)
    - [2.3. 框架](#23-%E6%A1%86%E6%9E%B6)
    - [2.4. 兼容性](#24-%E5%85%BC%E5%AE%B9%E6%80%A7)
    - [2.5. 编程思想](#25-%E7%BC%96%E7%A8%8B%E6%80%9D%E6%83%B3)
    - [2.6. 调试](#26-%E8%B0%83%E8%AF%95)
    - [2.7. 工程化](#27-%E5%B7%A5%E7%A8%8B%E5%8C%96)
    - [2.8. 安全性](#28-%E5%AE%89%E5%85%A8%E6%80%A7)
    - [2.9. 性能](#29-%E6%80%A7%E8%83%BD)
    - [2.10. 团队协作](#210-%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C)
    - [2.11. 交互设计](#211-%E4%BA%A4%E4%BA%92%E8%AE%BE%E8%AE%A1)
- [3. 前端边界](#3-%E5%89%8D%E7%AB%AF%E8%BE%B9%E7%95%8C)
- [4. HTML](#4-html)
    - [4.1. doctype](#41-doctype)
    - [4.2. 语义化](#42-%E8%AF%AD%E4%B9%89%E5%8C%96)
    - [4.3. 标签](#43-%E6%A0%87%E7%AD%BE)
        - [4.3.1. flow流式元素：](#431-flow%E6%B5%81%E5%BC%8F%E5%85%83%E7%B4%A0%EF%BC%9A)
        - [4.3.2. 看规范](#432-%E7%9C%8B%E8%A7%84%E8%8C%83)
    - [4.4. HTML扩展](#44-html%E6%89%A9%E5%B1%95)
        - [4.4.1. meta标签（增加元数据](#441-meta%E6%A0%87%E7%AD%BE%EF%BC%88%E5%A2%9E%E5%8A%A0%E5%85%83%E6%95%B0%E6%8D%AE)
        - [4.4.2. data-*属性（规范内-自定义的属性）](#442-data-%E5%B1%9E%E6%80%A7%EF%BC%88%E8%A7%84%E8%8C%83%E5%86%85-%E8%87%AA%E5%AE%9A%E4%B9%89%E7%9A%84%E5%B1%9E%E6%80%A7%EF%BC%89)
        - [4.4.3. link](#443-link)
        - [4.4.4. JSON-LD](#444-json-ld)
    - [4.5. Web无障碍/Accessibility](#45-web%E6%97%A0%E9%9A%9C%E7%A2%8Daccessibility)
    - [4.6. 工具](#46-%E5%B7%A5%E5%85%B7)
    - [4.7. 参考链接](#47-%E5%8F%82%E8%80%83%E9%93%BE%E6%8E%A5)
    - [全局属性](#%E5%85%A8%E5%B1%80%E5%B1%9E%E6%80%A7)
        - [class id style](#class-id-style)
        - [title](#title)
        - [tabindex](#tabindex)
        - [lang](#lang)
        - [dir](#dir)
        - [accesskey](#accesskey)
    - [（HTML5 全局属性）](#%EF%BC%88html5-%E5%85%A8%E5%B1%80%E5%B1%9E%E6%80%A7%EF%BC%89)
        - [data-*属性](#data-%E5%B1%9E%E6%80%A7)
        - [hidden](#hidden)
        - [contenteditable](#contenteditable)
        - [contextmenu](#contextmenu)
        - [draggable：(与HTML5drag结合用)](#draggable%EF%BC%9A%E4%B8%8Ehtml5drag%E7%BB%93%E5%90%88%E7%94%A8)
        - [dropzone 属性:](#dropzone-%E5%B1%9E%E6%80%A7)
        - [sppelcheck：](#sppelcheck%EF%BC%9A)
        - [translate 属性：](#translate-%E5%B1%9E%E6%80%A7%EF%BC%9A)
- [遗留](#%E9%81%97%E7%95%99)

<!-- /TOC -->

# 1. 前端做什么
用web标准技术html css js svg http等

做界面与交互

功能+美观+无障碍+安全+兼容+性能+体验

# 2. 知识图谱/技术栈
## 2.1. 语言
- js
- html
- css
- php
## 2.2. 行业标准
- DOM
- ES2018
- HTTP
- JSON
- XML
## 2.3. 框架
- React.js
- Angular.js
- jQuery
- Vue.js
- lodash
## 2.4. 兼容性
- IE等浏览器
- CSS3 新特性
- HTML5 新特性
- ES2018
- 移动端
## 2.5. 编程思想
- 函数式编程
- 面向对象
- 设计模式
## 2.6. 调试
- 浏览器
- Fiddler http
## 2.7. 工程化
- npm
- webpack
- postcss
## 2.8. 安全性
- XSS
- CSRF
- 加密解密
- 编解码
## 2.9. 性能
- 优化规则
- 开发者工具
- 浏览器原理
## 2.10. 团队协作
- git/svn
- 编码规范/eslint
- 文档管理
## 2.11. 交互设计


# 3. 前端边界
node、electron、react native、webRTC、WebGL、WEBAssembly

# 4. HTML
## 4.1. doctype
- 指定文档使用的标准和版本；
- 浏览器根据doctype决定使用哪种渲染模式；
- 没写会以怪异模式渲染（盒模型不同等待）
- 渲染模式

## 4.2. 语义化
- 元素、属性、属性值都有特定含义，应该遵循语义来写HTML
- 可读性、可维护性、搜索引擎优化、无障碍性

## 4.3. 标签
### 4.3.1. flow流式元素：
- heading 标题
- sectioning 章节
- phrasing 段落内容 p h
- Embedded 嵌入式内容 audio canvas
- interactive 可交互性内容 button a
- metadata 元数据元素 base link meta noscript script style title

### 4.3.2. 看规范

## 4.4. HTML扩展
### 4.4.1. meta标签（增加元数据
```HTML
<!-- 编码 -->
<meta charset="utf-8">

<!-- 指定http header -->
<meta http-equiv="Content-Security-Policy" content="script-src 'self'">

<!-- seo优化 -->
<meta name="keywords" content="关键词">
<meta name="description" content="页面介绍">

<!-- 移动设备的viewport 初始缩放比例，视口宽度 -->
<meta name="viewport" content="initial-scale=1">

<!-- 关闭IOS电话号码识别 -->
<meta name="format-detection" content="telphone=no">

<!-- 360等双核浏览器 指定渲染内核 -->
<meta name="renderer" content="webkit">

<!-- 指定IE渲染模式 -->
<meta name="X-UA-Compatibla" content="IE=Edge">
```
### 4.4.2. data-*属性（规范内-自定义的属性）
```HTML
  datasetAPI
    <el data-id=""/>
    el.dataset.id
```
### 4.4.3. link
- rel属性（relation关系，外部资源与当前页面的关系）
```html
<!-- 引入css-->
<link rel="stylesheet" href="">

<!-- 浏览器性能优化：dns预解析rel=dns-prefetch、资源预加载rel=prefetch、预渲染 rel=prerender -->
<link rel="dns-prefetch" href="">
<link rel="prefetch" href="">
<link rel="prerender" href="">

<!-- favicon：rel=icon -->
<link rel="icon" type="image/png" href="">

<!-- RSS：rel=alternate -->
<link rel="alternate" type="application/rss+xml" href="">
```

### 4.4.4. JSON-LD
  LD：linkdata 链接的数据 (直接在页面嵌json数据)
```js
<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Person",
  "name": "John Doe",
  "jobTitle": "Graduate research assistant",
  "affiliation": "University of Dreams",
  "additionalName": "Johnny",
  "url": "http://www.example.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "1234 Peach Drive",
    "addressLocality": "Wonderland",
    "addressRegion": "Georgia"
  }
}
//  应用例如分享页面时的数据
//  搜索引擎能识别等等
//  分享链接带有一些标题图片等信息
</script>
```

## 4.5. Web无障碍/Accessibility
- 一些Web开发者规范：
    - WCAG2.0
    - ARIA
- 提升无障碍性
    - img alt
    - noscript
    - input和label对应
    - 图片验证码与语音验证码
    - 文字背景对比度
    - 键盘可操作（tab modal focus）

## 4.6. 工具
- [W3C Validator（检查html合法性）](http://validator.w3.org/)
- emmet（插件）
- markdown（适合写文档）

## 4.7. 参考链接
- [HTML: The Living Standard](https://html.spec.whatwg.org/dev/)
- [Activating Browser Modes with Doctype](https://hsivonen.fi/doctype/)
- [Accessibility](https://www.w3.org/standards/webdesign/accessibility)
- Web Content Accessibility Guidelines 2.0
- [HTML5 Doctor: Semantics](http://html5doctor.com/element-index/)

## 全局属性
### class id style
### title
（兼容性最好的tooltip😂）
### tabindex
tab键控制次序
### lang
语言代码（利于语义化机器理解）（语言代码参考手册http://www.runoob.com/tags/html-language-codes.html）
### dir
文本方向（rtl ltr auto）
### accesskey 
元素的键盘访问快捷键（例值为'h'则不同浏览器不同OS有不同的操作方式，例chrome是 alt + 'h'）

## （HTML5 全局属性）
### data-*属性
属性名不要包含大写字母，在 data- 后必须至少有一个字符。
该属性可以是任何字符串
```
el.getAttribute("data-xx")
```
### hidden
不需要属性值，隐藏元素，原理是display:none
### contenteditable 
元素是否可编辑
### contextmenu
（说是目前只有firefox支持，亲测没效果
```
<p contextmenu="mymenu"></p>
<menu id="mymenu">
    <command label="xxx" onclick="fn()"/>
    <command label="xxx" onclick="fn()"/>
</menu>
```
### draggable：(与HTML5drag结合用)
```javascript

<div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>
<p id="drag1" draggable="true" ondragstart="drag(event)">这是一段可移动的段落。可把该段落拖入上下的矩形。</p>
<div id="div2" ondrop="drop(event)" ondragover="allowDrop(event)"></div>

function allowDrop(ev){
	ev.preventDefault();
}
function drag(ev){
	ev.dataTransfer.setData("Text",ev.target.id);
}
function drop(ev){
	var data=ev.dataTransfer.getData("Text");
	ev.target.appendChild(document.getElementById(data));
	ev.preventDefault();
}

```
### dropzone 属性:
规定当被拖动的数据在拖放到元素上时，是否被复制### 动或链接,无浏览器支持
### sppelcheck：
对元素的文本进行拼写检查
### translate 属性：
规定元素内容是否要翻译，=yes|no

# 遗留
表单元素  属性  datalist select下拉多选  input的multiple属性 button的type属性默认值
video不能嵌套img
p不能嵌套div
figure  dfn  cite 标签


---
    “因为你永远不知道你知道的有多深”
