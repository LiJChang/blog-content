---
title: Jinja2的妙用
date: 2022-08-05
tags: python
---

python programmer通常是在使用`flask`的時候接觸到jinja2的。不過除了在產生動態網頁會湧到模板語言。
在其他情境下模板語言也是非常有幫助的。這篇文章就來介紹我自己使用jinja2來產生machine learning報表來快速分享給組員。

## 需要模板引擎的緣由

如果我們要快速地使用python來寫出html報表
你可能會遇到這樣的code
```python
with open('file.html', 'w') as f:
    f.write('html content')
```
只要f.write一多，code很快就會變得雜亂不堪。
這時候要改code的人一看壹定是大翻白眼。

## 解決方案
上述做法顯然不好，view跟業務邏輯混在一起，顯然違反了
Seperation of concern(SoC)原則。
目標：
1. 能夠專心寫view
2. 講view跟業務邏輯分開。
jinja2樣版引擎就非常適合這樣的需求。

## 第一步: 寫模板(Template)

## 第二步: 注入資料

## 第三步: 產生文件