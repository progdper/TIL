## 마크다운 문법 정리

### 1. 제목(Header)
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

### 2. 강조(Emphasis)
*이탤릭체1*<br>
_이탤릭체2_

**볼드체1**<br>
__볼드체2__

**_이탤릭체와 볼드체_**

~~취소선~~

<u>밑줄</u>

<mark>형광펜</mark>

### 3.리스트(List)
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

### 4.링크(Links)
깃헙 블로그 https://jeon1787.github.io

깃헙 블로그 <https://jeon1787.github.io>

[깃헙 블로그](https://jeon1787.github.io)

[깃헙 블로그](https://jeon1787.github.io "링크 설명")

### 5.이미지(Images)
![이미지](./블로그_해볼까.png)<br>
이미지는 그냥 html의 <img>를 쓰자...

### 6.코드 강조
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

### 7.표(Table)
|왼쪽 정렬|가운데 정렬|오른쪽 정렬|
|:---|:---:|---:|
|왼쪽|가운데|오른쪽|
