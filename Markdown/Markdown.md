## 마크다운 문법 정리

###목차
1. [제목](#1장)
2. [강조](#2장)
3. [리스트](#3장)
4. [링크](#4장)
5. [이미지](#5장)
6. [코드 강조](#6장)
7. [표](#7장)
8. [인용문](#8장)
9. [수평선](#9장)
10. [줄바꿈](#10장)
11. [주석과 각주](#11장)

### 1. 제목(Header)<a id = "1장">
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

### 2. 강조(Emphasis)<a id = "2장">
*이탤릭체1*<br>
_이탤릭체2_

**볼드체1**<br>
__볼드체2__

**_이탤릭체와 볼드체_**

~~취소선~~

<u>밑줄</u>

<mark>형광펜</mark>

### 3.리스트(List)<a id = "3장">
1. 순서 있는 리스트
2. 순서 있는 리스트
3. 순서 있는 리스트

* 순서 없는 리스트
* 순서 없는 리스트
  * 하위 리스트
  * 하위 리스트

- 순서 없는 리스트
- 순서 없는 리스트
  - 하위 리스트
  - 하위 리스트

+ 순서 없는 리스트
+ 순서 없는 리스트
  + 하위 리스트
  + 하위 리스트

### 4.링크(Links)<a id = "4장">
깃헙 블로그 https://jeon1787.github.io

깃헙 블로그 <https://jeon1787.github.io>

[깃헙 블로그](https://jeon1787.github.io)

[깃헙 블로그](https://jeon1787.github.io "링크 설명")

### 5.이미지(Images)<a id = "5장">
![이미지](./블로그_해볼까.png)<br>
[![이미지에 링크 달기](https://img.shields.io/badge/Blog-jeon1787.github.io-brightgreen)](https://jeon1787.github.io)

### 6.코드 강조<a id = "6장">
`인라인(inline)`강조

블록(block) 강조
```java
for(int i=0; i<5; i++){
 System.out.println(i);
}
```

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

### 7.표(Table)<a id = "7장">
|왼쪽 정렬|가운데 정렬|오른쪽 정렬|
|:---|:---:|---:|
|왼쪽|가운데|오른쪽|

### 8.인용문(BlockQuote)<a id = "8장">
>인용문1
>>중첩된 인용문2
>>>중첩된 인용문3

### 9.수평선(Horizontal Rule)<a id = "9장">
***
---
___

### 10.줄바꿈(Line Breaks)<a id = "10장">
줄<br>바꿈

### 11.주석과 각주<a id = "11장">
<!--주석-->
마크다운 문법을 작성하고 있는 지금 시간은 1:43am이다.[^scala]

\[^scala]: 나는 졸리고 배고프다.(각주는 github에서 확인할 수 없는 듯하다.)
