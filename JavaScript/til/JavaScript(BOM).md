## Object Model

- 웹브라우저의 구성요서들은 하나하나 객체화되어 있다. 자바스크립트로 이 객체를 제어할 수 있게 된다. 이 객체들은 서로 계층적인 관계로 구조화되어 있다. BOM : 자바스크립트를 제어하는데서, 가장큰 테두리 역활을 한다.

- 객체화 : 

- window 객체 : 전역객체, window, frame
  docume(Document Object Model) : <body>,<img> 문서를 제어한다.
  BOM: window 객체의 프로퍼티에 저장되어있다.  브라우저 자체를 제어한다
  java Script Core : 브라우저 , 구글앱스스트리트, node.js를 제어 할 수있다. 

  Object , Array, Fuction DATE를 제어한다.

---

## 전역객체 

window 객체는 식별자 window를 통해서 얻을 수 있다.

---

## 사용자와 커뮤니케이션 하기

alert : 경고창이라 부르고, 사용자에게 정보를 제공하거나 디버깅으로 많이 사용함.

confirm : 확인창을 띄우고, true 랑 false를 리턴한다.

prompt : 사용자가 입력한 값을 받아서 자바스크립트가 얻어내는 기능.

---

## Location 객체

Location 객체는 문서의 주소와 관련된 객체로 Window 객체의 프로퍼티다. 이 객체를 이용해서 원도우의 문서 URL을 변경하고, 문서의 위치와 관련해서 다양한 정보를 얻을 수있다.

http://naver.com:80/module/?id=1#hash
protocal  host     port pathname search hash

location.href = 'http:www.daum.net'; :: 현재 문서를 www.daum.net 으로 이동시킨다.

location.href = location.href   location.reload() : 새로고침

----

## Navigator 객체

브라저의 정보를 제공하는 객체이다. 주로 호환성 문제등을 위해 사용한다.

console.dir(navigator); : 네비게이터 정보를  확인할 수 있다.

console.dir(navigator.appVersion); 브라우저 버전을 의미

console.dir(navigator.userAgent); : 브라우저 서버측으로 전송하는 USER-AGENT HTTP 헤더 내용

console.dir(navigator.platform); : 브라우저가 동작하는 운영체를 확인한다.

---

## 창 제어

_self는 새창이 뜨지 않고 그곳에 뜬다.
_blank 새창이 뜬다.































​    