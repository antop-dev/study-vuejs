## Naming Rule - Notation


### 케밥 표기법

> kebab-case, spinal-case, Train-Case, Lisp-case

하이픈으로 단어를 연결하는 표기법. HTML 태그의 id, class 속성으로 흔히 쓰임

```html
<div style="background-color: #fff;">
    <span id="s-01">span element</span>
</div>
```

### 스네이크 표기법

> snake case, snake_case, underscore case

단어를 밑줄문자로 구분하는 표기법

```sql
select user_name, address from tbl_users where age > 25; 
```

### 카멜 표기법

> camelCase, 단봉낙타 표기법

각 단어의 첫문자를 대문자로 표기하고 붙여쓰되, 맨처음 문자는 소문자로 표기함. 띄어쓰기 대신 대문자로 단어를 구분하는 표기 방식

```
String backgroundColor = "#fff";
String userName = "antop";
```

### 파스칼 표기법

> PascalCase

첫 단어를 대문자로 시작하는 표기법

```java
public class UserName {

}
```

### 헝가리안 표기법

> Hungarian notation

접두어를 사용하는 표기법

```
String strName = "antop";
boolean bBusy = false;
int nPrice = 0;
```