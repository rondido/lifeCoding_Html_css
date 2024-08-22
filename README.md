생활 코딩 CSS 강의 듣기

## CSS

```
li {
        color: red;
        text-decoration: underline;
      }
```

### 선택자

li : 선택자

id는 유니크한 값

class는 어떠한 대상의 관리하기 쉽도록 브로킹 하는 것

```
ul li {
        color: red;
      }
```

부모 선택자

선택자는 주어

### 가상클래스 선택자

```
a:active {
        color: green;
      }
      a:hover {
        color: yellow;
      }
```

hover는 마우스를 올려놓은 상태

마우스를 올려놓은 상태면 hover이면서 active한 상태입니다.

css는 뒤쪽 선언을 우선순위로 보여진다.
