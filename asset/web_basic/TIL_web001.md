# HTML 기본사용하는 방법

> 2022.03.05 : html과 css의 기초 사용법 이해
---

## web을 표현하는 언어
우리가 알고 있는 화면에 보이는 웹페이지는 기본 3개의 언어로 구성이 되어 있다.

- HTML : 화면의 구성형태 
  - 방갯수 거실 주방
- CSS : 화면의 표현되는 디자인 
  - 방1의 크기, 방향, 방2의 벽지색상, 주방의 크기
- Javascript : 화면에 표현되어있는 내용을 제어 
  - 방1,2를 합쳐서 방1로 재구성, 벽지색상을 변경, 복층개조, 문열리는 방식을 미닫이

  ---
  대부분의 기능들이 JS로 처리가 가능하기 때문에 시간이 지나면 HTML로 하기보다 JS로 처리하는 경우가 늘어남

  ---
  ## Markdown과 HTML의 관계?
  html문서를 보기쉽게 사용하기 편리해 개량한 것이 markdown<br />
  보다 전문성있게 디체일하게 작업하기 위해서는 HTML을 이용해야 한다.

---
### HTML 기본형태

``` html
<!DOCTYPE html>
<html lang="ko-KR">
  <head>
    <meat charset="UTF-8">
    <title>현재페이지 제목</title>
  </head>
  <body></body>
</html>
```
```html
<html>                     ...</html>---
  <head>                   ...</head>---
    <meta charset="UTF-8">
    <title>타이틀</title>
  </head>
  <body>                   ...</body>---




  </body>
</html>
```