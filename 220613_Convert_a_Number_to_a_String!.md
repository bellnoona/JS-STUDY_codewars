# Convert a Number to a String!

## Requirement

<p>We need a function that can transform a number into a string.   
What ways of achieving this do you know?</p>

`숫자를 문자열로 변환하라.`

## Example

```js
123 --> "123"
999 --> "999"
```

<br>

### 나의 시도

> why?  
> 함수 안으로 들어오는 것이 숫자인지 판별하기 위해 `isNaN()`함수를 사용하였고, 들어오는 인자 `num`를 `toString()`함수를 통해 문자열로 변환시켜주었다.  
> 처음에 `return`을 안하고 `console.log()`문을 찍어서 게속 오류가 났다.

```js
function numberToString(num) {
  // Return a string of the number here!
  if (!Number.isNaN(num)) {
    return num.toString();
  }
}
```
