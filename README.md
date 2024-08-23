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

### font-size

px vs em vs rem

em, rem의 경우 사용자가 브라우저에 설정을 바꾸면
설정에 따라서 폰트의 크기가 달라진다.

rem 사용 권장
폰트크기를 조정할 수 있는 사용자의 권리

### text-align

```
text-align: justify
```

양쪽이 균등하게 분배된다.

```
 p {
        font-size: 5rem;
        font-family: arial, Verdana, Geneva;
      }
```

font- family에 ,를 사용하여 왼쪽부터 폰트가 존재하지 않으면 그 다음 폰트가 적용되게 됨.

serif vs sans serif

serif는 글꼴에서 사용하는 장식 의미.

sans는 부정의 표현

![Alt text](image.png)

### cascading style sheet

cascading

웹 브라우저 html 해석을 하는 기계

html 기본적인 디자인 존재

user

author

서로 조화를 이뤄서 웹을 만들어가는 철학을 만들기 위해 만든 것이 cs

대가는 우선 순위
웹 브라우저의 기본 디자인
사용자도 원하는 디자인
컨텐츠를 생산하는 디자인

우선순위
웹브라우저 < 사용자 < 저자
