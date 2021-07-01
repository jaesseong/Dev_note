# 마크다운<sup>Markdown</sup>
------------
목차
----
- [마크다운<sup>Markdown</sup>이란?](#concept)
- [마크업 문법<sup>Markup Syntax</sup>](#syntax)
  - [제목<sup>Header</sup>](#header)
  - [강조<sup>Emphasis</sup>](#emphasis)
  - [수평선<sup>Horizontal Rules</sup>](#horizontal)
  - [링크<sup>Links</sup>](#links)
  - [이미지<sup>Images</sup>](#images)
  - [Blockquotes](#blockquotes)
  - [첨자<sup>Script</sup>](#script)


## <div id="concept">마크다운<sup>Markdown</sup>이란?</div>


마크다운(markdown)은 2004년에 존 그루버와 에런 스워츠의 협업을 통해 만들어진 일반 텍스트 기반의 경량 마크업 언어이다.

> #### 마크업 언어<sup>Markup Language</sup>란?
> 태그 등을 이용하여 문서나 데이터의 구조를 명기하는 언어

## <div id="syntax">마크업 문법<sup>Markup Syntax</sup></div>

### <div id="header">헤더<sup>Header</sup></div>

- #### h1 
  큰 제목, 문서 제목
  ##### 실행 코드
  ```
  # This is an <h1> tag
  ```
  ##### 결과
  # This is an `<h1>` tag
  ##### 실행 코드
  ```
  This is an <h1> tag
  ===
  ```
  ##### 결과
  This is an `<h1>` tag
  ===
- #### h2
  중간 제목, 부 제목
  ##### 실행 코드
  ```
  ## This is an <h2> tag
  ```
  ##### 결과
  ## This is an `<h2>` tag
  ##### 실행 코드
  ```
  This is an <h2> tag
  ---
  ```
  ##### 결과
  This is an `<h2>` tag
  ---
- #### h3 ~ h6
  소 제목  
  ##### 실행 코드
  ```
  ### This is an <h3> tag
  #### This is an <h4> tag
  ##### This is an <h5> tag
  ###### This is an <h6> tag
  ```
  ##### 결과
  ### This is an `<h3>` tag
  #### This is an `<h4>` tag
  ##### This is an `<h5>` tag
  ###### This is an `<h6>` tag

### <div id="emphasis">강조<sup>Emphasis</sup></div>
- #### 볼드체<sup>bold</sup>
  굵게쓰기  
  ##### 실행 코드
  ```
  **This text will be bold**
  __This will also be bold__
  ```
  ##### 결과
  **This text will be bold**
  __This will also be bold__
- #### 이탤릭체<sup>italic</sup>
  기울여쓰기  
  ##### 실행 코드
  ```
  *This text will be italic*
  _This will also be italic_
  ```
  ##### 결과
  *This text will be italic*
  _This will also be italic_


### <div id="horizontal">수평선<sup>Horizontal Rules</sup></div>
`-`, `*` 또는 `_`를 3개 이상 입력  
##### 실행 코드
```
---
***
___
```
##### 결과
---
***
___

### <div id="links">링크<sup>links</sup>
- #### URL links 
  URL 입력시 자동적으로<sup>Automaticl</sup> 하이퍼링크 등록  
  ##### 실행 코드
  ```
  http://github.com/
  ```
  ##### 결과
  http://github.com/
- #### Inline links
  문구에 하이퍼링크 등록
  ##### 실행 코드
  ```
  [깃 허브](http://github.com/ "Github")
  ```
  ##### 결과
  [깃 허브](http://github.com/ "Github")
- #### 참조 링크
  문서 내에 같은 주소의 하이퍼링크를 효율적으로 작성할 수 있음  
    
  ※ 참조되어지는 행과 참조할 정보를 기록하는 행은 한 행 이상의 거리가 필요  
  ##### 실행 코드
  ```
  [깃 허브][1]는 최고의 협업 사이트입니다.
  [깃 허브][github]를 경험해보고 싶다면 [이 곳][1]을 클릭해주세요.

  [1]:http://github.com/ "Github"
  [github]:http://github.com/ "Github"
  ```
  ##### 결과
  [깃 허브][1]는 최고의 협업 사이트입니다.  
  [깃 허브][github]를 경험해보고 싶다면 [이 곳][1]을 클릭해주세요.  

  [1]:http://github.com/ "Github"
  [github]:http://github.com/ "Github"

### 리스트<sup>Lists</sup>
- #### 순서가 있는 리스트<sup>Ordered Lists</sup>  
  ※ 적힌 숫자와 상관없이 순서대로 번호가 매겨진다.
  ##### 실행 코드
  ```
  1. item 1
  1. item 2
  1. item 3
    1. item 3a
    1. item 3b
  ```
  ##### 결과
  1. item 1
  1. item 2
  1. item 3  
      1. item 3a
      1. item 3b

- #### 순서가 없는 리스트<sup>Unordered Lists</sup>
  ##### 실행 결과
  ```
  - item 1
    - item 1-1
      - item 1-1-1
  * item 2
    * item 2-1
      *item 2-1-1
  + item 3
    + item 3-1
      + item 3-1-1
  ```
  ##### 결과
  - item 1
    - item 1-1
      - item 1-1-1
  * item 2
    * item 2-1
      * item 2-1-1
  + item 3
    + item 3-1
      + item 3-1-1

## <div id="images">이미지<sup>Images</sup></div>
- #### Link image
  이미지 오른쪽 마우스 클릭 -> 이미지 주소 복사 -> URL 입력
  ##### 실행 결과
  ```
  ![Bird](https://cdn.pixabay.com/photo/2021/06/27/17/50/redstart-6369564__480.jpg)
  ```
  ##### 결과
  ![Bird](https://cdn.pixabay.com/photo/2021/06/27/17/50/redstart-6369564__480.jpg)

- #### Inline image  
  로컬 저장소의 경로를 입력  
  ##### 실행 코드
  ```
  ![Squirrel](./image/squirrel.webp "다람쥐")
  ```
  ##### 결과
  ![Squirrel](./image/squirrel.webp "다람쥐")

- #### Image link  
  Combination of Image and Link  
  ##### 실행 코드
  ```
  [![Squirrel](./image/squirrel.webp)](http://github.com)
  ```
  ##### 결과
  [![Squirrel](./image/squirrel.webp)](http://github.com)
  
## <div id="blockquotes">Blockquotes</div>
##### 실행 코드
```
As Kanye West said:

> We're living the future so
> the present is our past.
```
##### 결과
As Kanye West said:

> We're living the future so  
> the present is our past.

## <div id="script">첨자<sup>Script</sup></div>
- #### 위첨자<sup>Superscript</sup>
##### 실행 결과
```
문구<sup>윗첨자</sup>
```
##### 결과
문구<sup>윗첨자</sup>
- #### 아래첨자<sub>Subscript</sub>
##### 실행 결과
```
문구<sub>아랫첨자</sub>
```
##### 결과
문구<sub>아랫첨자</sub>

## <div id="code">코드<sup>Code</sup></div>
- #### Inline code
##### 실행 코드
```
I think you should use an  
`<addr>` element here instead.
```
##### 결과
I think you should use an  
`<addr>` element here instead.

- #### 펜스<sup>Fences</sup>
##### 실행 코드
~~~
```
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
~~~
##### 결과
```
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
##### 실행 코드
```
~~~
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
~~~
```
##### 결과
~~~
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
~~~
※ 펜스 내에 \`\`\`을 적고 싶으면 \~\~\~ 펜스를 사용, 반대도 가능

- #### 문법 강조<sup>Syntax highlighting</sup>
##### 실행 코드
~~~
``` javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
~~~
##### 결과
``` javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
