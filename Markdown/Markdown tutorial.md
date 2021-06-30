# 마크다운<sup>Markdown</sup>
------------
마크다운<sup>Markdown</sup>이란?
------------
마크다운(markdown)은 2004년에 존 그루버와 에런 스워츠의 협업을 통해 만들어진 일반 텍스트 기반의 경량 마크업 언어이다.

> #### 마크업 언어<sup>Markup Language</sup>란?
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

### 강조<sup>Emphasis</sup>
- 볼드체<sup>bold</sup> : 굵게쓰기
  ```
  **This text will be bold**
  __This will also be bold__
  ```
  **This text will be bold**
  __This will also be bold__
- 이탤릭체<sup>italic</sup> : 기울여쓰기
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

### 링크<sup>links</sup>
- URL links : URL 입력시 자동적으로<sup>Automaticl</sup> 하이퍼링크 등록
  ```
  http://github.com/
  ```
  http://github.com/
- Inline links : 문구에 하이퍼링크 등록
  ```
  [깃 허브](http://github.com/ "Github")
  ```
  [깃 허브](http://github.com/ "Github")
- 참조 링크 : 문서 내에 같은 주소의 하이퍼링크를 효율적으로 작성할 수 있음
  ※ 참조되어지는 행과 참조할 정보를 기록하는 행은 한 행 이상의 거리가 필요
  ```
  [깃 허브][1]는 최고의 협업 사이트입니다.
  [깃 허브][1]를 경험해보고 싶다면 [이 곳][1]을 클릭해주세요.
  
  [1]:http://github.com/ "Github"
  ```
  [깃 허브][1]는 최고의 협업 사이트입니다.
  [깃 허브][1]를 경험해보고 싶다면 [이 곳][1]을 클릭해주세요.
  
  [1]:http://github.com/ "Github"  
- 함축적 링크 사용 : 번호가 아닌 함축적 의미를 담은 문구를 이용해 참조
  ```
  [깃 허브][github]는 최고의 협업 사이트입니다.
  [깃 허브][github]를 경험해보고 싶다면 [이 곳][github]을 클릭해주세요.
  
  [github]:http://github.com/ "Github"
  ```
  [깃 허브][github]는 최고의 협업 사이트입니다.
  [깃 허브][github]를 경험해보고 싶다면 [이 곳][github]을 클릭해주세요.
  
  [github]:http://github.com/ "Github"
  
  
  

  
  
  
