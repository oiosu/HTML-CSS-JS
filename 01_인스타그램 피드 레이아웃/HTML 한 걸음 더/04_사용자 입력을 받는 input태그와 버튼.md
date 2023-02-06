# 04_사용자 입력을 받는 input태그와 버튼

##### input 태그는 필수적으로 name과 type이라는 속성이 있어야한다. 

```html
<input type="text" name="" />
```

> * type에 어떠한 값을 주는지에 따라 여러 형태로 보여질 수 있다. 



```html
    <!--다음 4개는 같은 로그인 버튼 형식으로 보여진다.  -->
    <!-- submit은 버튼 형식 -->

    <!-- 1. form 제출됨 -->
    <input type="submit" value="로그인"/>
    <!-- 2. form 제출안됨 -->
    <input type="button" value="로그인"> 
    <!-- 3. form 제출됨  -->
    <button type="submit">로그인</button>
    <!-- 3. form 제출됨  -->
    <button>로그인</button>
```

