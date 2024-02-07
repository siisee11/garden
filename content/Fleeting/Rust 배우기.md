---
tags:
  - public
---
## 설치 및 실행

[Installation](https://www.rust-lang.org/tools/install)

[Getting Started](https://www.rust-lang.org/learn/get-started)

## 예제

### First project 
[Guessing Game](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html#programming-a-guessing-game)
* let, mut, match

### Common Programming Concepts

* Variables and mutability
	* Rust는 기본적으로 immutable
	* mutable하게 쓰려면 mut 지시자 붙혀야함
* Constant
	* 전역적으로 사용가능
	* 정의시 타입 무조건 명시
	* 절대 못바꿈
	* Runtime에 알 수 있는 수로 정의 못함.
* Shadowing
	* 같은 변수이름을 쓸 수 있게 해주는 것
	* 재선언시 타입도 변경 가능
```
	let x = 5; let x = x + 1;
```

### [Data Types](https://doc.rust-lang.org/book/ch03-02-data-types.html)

* Scalar Type
	* 하나의 값을 표현하는 타입
	* intergers, floating-point numbers, Booleans, and characters
	* 각각 타입들은 링크 타고 가서 더 자세히 보면됨.
* Compound Type
	* 여려개의 값을 하나로 묶은 타입
	* tuples, arrays
	* Tuples
		* Fixed size
		* unit = empty tuple
	* Arrays
		* 모든 element 가 같은 타입
		* Fixed length
		* array는 데이터를 heap이 아닌 stack에 할당하고 싶을때 유용함.

### [Functions](https://doc.rust-lang.org/book/ch03-03-how-functions-work.html)

펑션은  Statement와 Exmpressions로 이루어져있음.
* Statements : 뭔가하고 값을 리턴하지 않는 지시문
	* 예) Assignment 구문
		* 참고로 c랑 ruby는 assignment 구문도 값을 리턴한다고 한다.
* Expressions: 결과값을 내뱉는 지시문
	* Expression은 semicolon이 없다.
	* function의 결과값은 마지막 expression의 결과값

