# 마크다운<sup>Markdown</sup>
------------
마크다운<sup>Markdown</sup>이란?
------------
마크다운(markdown)은 2004년에 존 그루버와 에런 스워츠의 협업을 통해 만들어진 일반 텍스트 기반의 경량 마크업 언어이다.

> 마크업 언어<sup>Markup Language</sup>란?
> ----------
> 태그 등을 이용하여 문서나 데이터의 구조를 명기하는 언어

마크업 문법<sup>Markup Syntax</sup>
----
### 헤더<sup>Header</sup>
- h1 : 큰 제목, 문서 제목
  ```
  # This is an <h1> tag
  ```
  # This is an `<h1>` tag
  ```
  This is an <h1> tag
  ===
  ```
  This is an `<h1>` tag
  ===
- h2 : 중간 제목, 부 제목
  ```
  ## This is an <h2> tag
  ```
  ## This is an `<h2>` tag
  ```
  This is an <h2> tag
  ---
  ```
  This is an `<h2>` tag
  ---
- h3 ~ h6 : 소 제목
  ```
  ### This is an <h3> tag
  #### This is an <h4> tag
  ##### This is an <h5> tag
  ###### This is an <h6> tag
  ```
  ### This is an `<h3>` tag
  #### This is an `<h4>` tag
  ##### This is an `<h5>` tag
  ###### This is an `<h6>` tag

### 강조^Emphasis^
- 볼드체^bold^ : 굵게쓰기
  ```
  **This text will be bold**
  __This will also be bold__
  ```
  **This text will be bold**
  __This will also be bold__
- 이탤릭체^italic^ : 기울여쓰기
  ```
  *This text will be italic*
  _This will also be italic_
  ```
  *This text will be italic*
  _This will also be italic_


### 수평선<sup>Horizontal Rules</sup>
`-`, `*` 또는 `_`를 3개 이상 입력
```
---
***
___
```
---
***
___

### 링크^links^
- URL links : URL 입력시 자동적으로^Automaticl^ 하이퍼링크 등록
  ```
  주소
  http://github.com/jaesseong
  ```
  http://github.com/jaesseong
- Inline links : 문구에 하이퍼링크 등록
  ```
  [주소에 대한 설명](주소)
  [Jaeseong's Github](http://github.com/jaesseong)
  ```
  [Jaeseong's Github](http://github.com/jaesseong)
- 참조 링크
  ```
  [주소에 대한 설명] [1]
  [google] [1]
  [참조 번호] : 주소
  [1] : http://google.co.kr
  ```
  
  [Jaeseong's Github][1]
  [1]:http://github.com/jaesseong "라면"
  
  
  
