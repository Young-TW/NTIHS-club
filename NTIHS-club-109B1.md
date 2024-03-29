---
tags: 網頁設計社 109
---

# 網頁設計社 課前預習 DAY1 (109下)

[TOC]
### 講師：
- Young#0001 
- xiao xigua#8597

## 網頁前端基本介紹
:::warning
:loudspeaker: 以上都是會教的東西，那大家也可以先上網查，先預習，這樣對於之後教學時，可以更快的了解講師在講什麼。
:::

[TOC]

學習：[W3C School](https://www.w3schools.com/html/)
練習：[html cafe](https://html.cafe/)

## HTML是甚麼?
超文本標記語言 (Hypertext Markup Language, HTML)

使用標籤來排序要顯示的內容

==<標籤>== 為開頭
==</標籤>== 為結尾

```htmlmixed=
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
    <title>This is title</title>
  </head>
  <body>
    <p>hello, world</p>
  </body>
</html>
```

### HTML 常見標籤
- **\<h1~h6>** - 標題 (由h1最大到h6最小)
- **\<ul>** - 列表
- **\<div>** - 定義一個區域 (div在隔離出部分可含段落、標題、表格等)
- **\<section>** - 定義一個區域 (章節，表示相關但是不同的段落)
- **\<a>** - 超連結
- **\<span>** - 行內元素
- **\<p>** - 文字段落
- **\<img>** - 圖片
- **\<br>** - 換行
### HTML 常見標籤 字體修改

| 語法 |  描述  | 呈現樣子 |
|:---:|:-----:|:-----:|
|\<b>| 粗體 | <b>abc<b> |
|\<strong>| 粗體 | <strong>abc<strong> |
|\<i>| 斜體 | <i>abc<i> |
|\<em>| 斜體 | <em>abc<em> |
|\<mark>| 螢光筆 | <mark>abc<mark> |
|\<small>| 小字 | <small>abc<small> |
|\<del>| 刪除線 | <del>abc<del> |
|\<ins>| 底線 | <ins>abc<ins> |
|\<sub>| 下標 | abc<sub>abc<sub> |
|\<sup>| 上標 | abc<sup>abc<sup> |

## CSS是甚麼?
階層式樣式表(Cascading Style Sheets,CSS)

是用來輔助HTML加上不同的樣式

```htmlmixed=
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
    <title>This is title</title>
    <style>h1 {color:blue;}</style>           <!-- here -->
  </head>
  <body>
    <h1>Hello world!</h1>
    <p style=”color:green;”>hello, world</p>  <!-- here -->
  </body>
</html>
```

### CSS使用方法

- 寫在HTML```<style>```標籤裡面的CSS
- 在要使用CSS的標籤內直接加入style=

```htmlmixed=
<style>h1 {color:blue;}</style>              <!-- 寫在HTML的<style>標籤內 -->
<p style=”color:green;”>hello, world</p>     <!-- 在要使用CSS的標籤內加入CSS -->
```

### CSS常見標籤


```css=
body  {background-color: powderblue;}        <!-- 背景顏色: -->
h1   {color: blue;}                          <!-- 文字顏色: -->

p {
color: red;                                  <!-- 文字顏色: -->
font-family: courier;                        <!-- 文字字體: -->
font-size: 160%;                             <!-- 文字大小: -->
}
```

### 顏色進階介紹

從RGB三原色或是十六進位或是其他方法來調整顏色

- 三原色用法:  (<span style=color:red>0~255</span>,<span style=color:green>0~255</span>,<span style=color:blue>0~255</span>)  

- 十六進位的用法:  #<span style=color:red>00</span><span style=color:green>00</span><span style=color:blue>00</span> (原理和RGB一樣)

## JavaScript是甚麼?

 JavaScript是一種進階的、直譯的程式語言
 


### 在HTML中使用JavaScript

```htmlembedded=
<!--  直接寫在HTML裡的JavaScript  -->
<script>
    console.log("Hello World!");
</script>

<!-- 寫在另外的js檔案  -->
<script src="/main.js"></script>
```
---


### JavaScript在前端(FrontEnd)的功用
- 與用戶互動
- 做動畫
---


### JavaScript的其他功用
-- [Node.js](https://www.google.com.tw/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjJqY2o3tXvAhUlw4sBHftMB34QFjABegQIAhAE&url=https%3A%2F%2Fnodejs.org%2F&usg=AOvVaw1tY2p-vJFWJmxWlq4sTxCn)的出現讓JS可以在瀏覽器以外的地方運行
- 後端(BackEnd)
- 軟體
- 遊戲


---
### 目前主流三大前端框架
#### 使用框架原因能夠==快速開發==
- Vue
- React
- Angular

## Node.js的出現

- 原本的前端工程師能夠轉行成全端工程師
- 可以用JavaScript做更多事情


## 最後補充


### 前面你們聽到的前端、後端、全端是甚麼?
- FrontEnd(前端)一個網頁畫面呈現的地方就是你在看YouTube時所看到的頁面就叫前端

- BackEnd(後端)一個網頁處理資料的地方就是你看YouTube時你影片來源的地方，一般人可能會說伺服器(Server)

- FullStack(全端)就是FrontEnd+BackEnd(前端加後端)
 ~~[[補充]](https://zh.wikipedia.org/zh-tw/%E5%89%8D%E7%AB%AF%E5%92%8C%E5%90%8E%E7%AB%AF)~~
