---
layout: post
title: "Hyperlink"
description:
headline:
modified: 2020-02-27
category: HTML
tags: [HTML, TAG]
imagefeature:
mathjax:
chart:
share: true
comments: true
featured: true
---

## 1. href 어트리뷰트

<span class="p">HyperText의 Hyper</span>는 컴퓨터 용어로서 텍스트 등의 정보가 동일 선상에 있는 것이 아니라 <span class="y">다중으로 연결되어 있는 상태를 의미</span>한다.

이것은 HTML의 가장 중요한 특징인 link의 개념과 연결되는데 기존 문서나 텍스트의 선형성, 고정성의 제약에서 벗어나 사용자가 원하는 순서대로 원하는 정보를 취득할 수 있는 기능을 제공한다. <span class="y">한 텍스트에서 다른 텍스트로 건너뛰어 읽을 수 있는 이 기능을 하이퍼링크(hyper link)</span>라 한다.

<span class="p">HTML link</span>는 hyperlink를 의미하며 a(anchor) tag가 그 역할을 담당한다.

<div class="code"><script async src="//jsfiddle.net/Jangyusu/hLga9o84/37/embed/html,result/dark/"></script></div>

<span class="p">href 어트리뷰트</span>는 이동하고자 하는 파일의 위치(경로)를 값으로 받는다. 경로(path)란 파일 시스템 상에서 <span class="y">특정 파일의 위치를 의미</span>한다.

### 1.1 디렉터리(Directory)

<span class="p">디렉터리</span>는 파일과 다른 디렉터리를 갖는 파일 시스템 내의 존재물로서 폴더라고도 불리운다.

<span class="g">루트 디렉터리</span>  
파일 시스템 계층 구조 상의 최상위 디렉터리이다.  
Unix: /  
Windows: C:\

<span class="g">홈 디렉터리</span>  
시스템의 사용자에게 각각 할당된 개별 디렉터리이다.  
Unix: /Users/{계정명}  
Windows: C:\Users\{계정명}

<span class="g">작업 디렉터리</span>  
작업 중인 파일의 위치한 디렉터리이다.  
./

<span class="g">부모 디렉터리</span>  
작업 디렉터리의 부모 디렉토리이다.  
../

### 1.2 파일 경로(File path)

<span class="p">파일 경로</span>는 파일 시스템에서 파일의 위치를 나타내는 방법이다. 경로에는 절대경로와 상대경로가 있다.

<span class="g">절대경로(Absolute path)</span >  
현재 작업 디렉터리와 관계없이 특정 파일의 절대적인 위치를 가리킨다. 루트 디렉터리를 기준으로 파일의 위치를 나타낸다.  
http://www.mysite.com/index.html  
/Users/leeungmo/Desktop/myImage.jpg  
C:\users\leeungmo\Desktop\myImage.jpg  
/index.html

<span class="g">상대경로(Relative path)</span >  
현재 작업 디렉터리를 기준으로 특정 파일의 상대적인 위치를 가리킨다.  
./index.html  
../dist/index.js  
../../dist/index.js  
index.html  
html/index.html

href 어트리뷰트에 사용 가능한 값은 아래와 같다.

<span class="g">절대 URL</span>  
웹사이트 URL (href=”http://www.example.com/default.html”)

<span class="g">상대 URL</span>  
자신의 위치를 기준으로한 대상의 URL (href=”html/default.html”)

<span class="g">fragment identifier</span>  
페이지 내의 특정 id를 갖는 요소에의 링크 (href=”#top”)

<span class="g">메일</span>  
mailto:

<span class="g">script</span>  
href=”javascript:alert(‘Hello’);”

<div class="code"><script async src="//jsfiddle.net/Jangyusu/hLga9o84/39/embed/html,result/dark/"></script></div>

<span class="p">fragment identifier</span>를 이용한 페이지 내부 이동 방법은 다음과 같다.

<div class="code"><script async src="//jsfiddle.net/Jangyusu/hLga9o84/41/embed/html,result/dark/"></script></div>

## 2. target 어트리뷰트

<span class="p">target 어트리뷰트</span>는 링크를 클릭했을 때 윈도우를 어떻게 오픈할 지를 지정한다.

<span class="g">\_self</span>  
링크를 클릭했을 때 연결문서를 현재 윈도우에서 오픈한다 (기본값)

<span class="g">\_blank</span>  
링크를 클릭했을 때 연결문서를 새로운 윈도우나 탭에서 오픈한다

<div class="code"><script async src="//jsfiddle.net/Jangyusu/hLga9o84/43/embed/html,result/dark/"></script></div>

<span class="b">출처 : https://poiemaweb.com/</span>
