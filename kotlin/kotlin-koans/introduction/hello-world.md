# Hello, World!

### Task - Simple Functions

Check out the [function syntax](https://kotlinlang.org/docs/basic-syntax.html#functions) and change the code to make the function `start` return the string `"OK"`

```kotlin
fun start(): String = TODO()
```

### Answer

```kotlin
fun start(): String = "OK"
```

### Learning

#### Functions

`Int` 파라미터 2개와 `Int` 반환 타입을 가지는 함수

```kotlin
fun sum(a: Int, b: Int): Int {
    return a + b
}
```

함수 본문이 식으로 표현될 경우, 반환 타입이 추론 가능하다.

```kotlin
fun sum(a: Int, b: Int) = a + b
```

함수가 의미없는 값을 반환할 경우

```kotlin
fun printSum(a: Int, b: Int): Unit {
    println("sum of $a and $b is ${a + b}")
}
```

`Unit` 타입은 생략이 가능하다.

```kotlin
fun printSum(a: Int, b: Int) {
    println("sum of $a and $b is ${a + b}")
}
```
