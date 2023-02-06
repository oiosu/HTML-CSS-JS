# 07_태그를 설명해주는 label 태그

```html
<!-- label 태그 -->
        <div>
            <!-- 1. label 태그에 대한 설명을 input로 할 수 있다. -->
            <!-- : label 태그 안에 input태그  -->
            <label>모자 : 
                <input type="checkbox" name="kind" value="hat">
            </label>

            <!-- 2. label 속성에 for 추가 -->
            <!-- label for top 아이디와 동일한 값을 가진 속성에 label에 대한 설명이 담긴 것  -->
            <label for="top"> 상의 : </label>
            <input type="top" type="checkbox" name="kind" value="top">
        </div>

```









```html
<!-- label 태그 정리 -->
        <div>
            <label> 이메일
                <input type="email" name="" id="">
            </label>
        </div>
        
        <div>
            <label for=""> 비밀번호
                <input type="password" name="" id="">
            </label>
        </div>

```

