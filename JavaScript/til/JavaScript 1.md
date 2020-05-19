jquery = js를 편하게 사용하기 위해 만들어 놓은 것.

JavaScript : 웹브라우저,HTML을 프로그래밍적으로 제어해준다. 

avascript : HTML을 프로그래밍적으로 제어해준다. 

 HTML : 정보를 제어한다.

CSS : 디자인 담당

id 가 a 일 때, # a 면 그부분을 선택
클래스가 b 일 때, # b면 그부분 선택
class 가 a 일 때 . a 로 그 부분을 선택한다. (css에서)

---

HTML 안에 javascript 삽입

```html
<!DOCTYPE html>
<html>
<body>
    <input type="button" onclick="alert('Hello world')" value="Hello world" />
</body>
</html>
```

windows.onload = 웹브라우저가 다 실행되고 마지막에 실행해라

외부 파일 .js를 실행시킬 때, <body>태크 뒤에 위치하는 것이 바람직하다.