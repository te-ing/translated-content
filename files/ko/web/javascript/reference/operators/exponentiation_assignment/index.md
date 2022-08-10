---
title: 거듭제곱 할당 (**=)
slug: Web/JavaScript/Reference/Operators/Exponentiation_assignment
tags:
  - Assignment operator
  - JavaScript
  - Language feature
  - Operator
  - Reference
translation_of: Web/JavaScript/Reference/Operators/Exponentiation_assignment
browser-compat: javascript.operators.exponentiation_assignment
---
{{jsSidebar("Operators")}}

거듭제곱 할당 연산자(`**=`)는 오른쪽 피연산자의 값으로 변수를 거듭제곱한 결과를 다시 변수에 할당합니다.

{{EmbedInteractiveExample("pages/js/expressions-exponentiation-assignment.html")}}

## 구문

```js
x **= y // x = x ** y
```

## 예제

### 거듭제곱 할당 사용하기

```js
// bar = 5
// 위와 같은 변수를 가정할 때

bar **= 2     // 25
bar **= 'foo' // NaN
```

## 명세

{{Specifications}}

## 브라우저 호환성

{{Compat}}

## 같이 보기

- [JavaScript 안내서의 할당 연산자](/ko/docs/Web/JavaScript/Guide/Expressions_and_Operators#할당_연산자)
- [거듭제곱 연산자](/ko/docs/Web/JavaScript/Reference/Operators/Exponentiation)