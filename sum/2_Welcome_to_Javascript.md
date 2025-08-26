# 2.0 Your First JS Project
## MAC에서 파일 만들기.
터미널에 다음을 복사 및 붙여넣기
> $ mkdir 파일명

## HTML파일과 JS파일 연결하기
```html
<body>
    <script src="app.js"></script> //app은 자바스크립트 파일명.
</body>
```

---

# 2.1 기본적인 데이터 타입

## Number
- **정수 (Integer)**: `1`, `2`, `3`, `4` ...
- **실수 (Float)**: `1.555`, `2.545345` ...

## String
- 문자열은 **처음부터 끝까지 문자(Text)로 구성**되어 있다.
- 큰따옴표(`" "`) 또는 작은따옴표(`' '`)로 감싸서 표현한다.

```js
"Hello," + " My name is Nico"
// 출력: Hello, My name is Nico
```

👉 문자열끼리 `+` 연산을 하면 두 문자열을 **이어 붙여(concatenate)** 출력한다.

---

# 2.2 변수

## 선언
```js
const 변수 = 데이터;
```
const는 변수 앞에 붙어 해당 변수나 값이 변경되지 않음을 나타내는 키워드이다.

## 변수 이름 짓기
단어가 여러개인 변수를 지을 때애는, 두번째 단어부터 앞글자를 대문자로. -> Camelcase

> ex) myName, veryLongVariableName

---

# 2.3 let

## 재할당
const는 한번 값을 주면 재할당 불가능.
재할당을 하고싶으면, let을 써야함.

```js
const name = "sj";
name = "ksj"; ❌

console.log(name);
```

```js
let name = "sj";
name = "ksj"; ✅

console.log(name);
```

## var
재할당, 재선언 가능.
```js
var name = "sj";
var name = "ksj"; ✅
name = "kkssjj"l ✅

console.log(name);
```
let과 const가 없었을때 쓰던 선언방식.(구버전)

> 저자는 새로운 방식(let,const)을 선호함.

---
