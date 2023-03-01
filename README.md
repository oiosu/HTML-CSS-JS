# 🐌 이 강의를 선택하고 공부하는 이유 
그동안 알고 있었던 HTML/CSS 개념적인 부분들을 복습하는 시간을 가지고 싶은 마음에 이 강의를 듣게 되었습니다. <br>
6개월 풀스택 강의 이후 프론트엔드 개발자가 되기위한 역량들을 찾아보며 HTML, CSS 개념적인 부분들도 중요하다는 것을 느꼈고, <br>
알고 있는 내용들도 계속 잊지 않고자 강의들을 들으며 공부 내용을 탐색하였습니다. <br>
또한 그와함께 클론코딩을 어떻게 하면 잘할 수 있을지에 대한 고민을 하고 있으며, 라이트닝 토크를 통해 그동안 배웠던 HTML, CSS, JS 개념을  활용하여 <br>
홈페이지를 직접 만들어 보는 프로젝트를 진행하고 있습니다. 


---



# Instagram_clone_coding
[📁 01_기본구조잡기](https://github.com/oiosu/Instagram_clone_coding/blob/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/01_%EA%B8%B0%EB%B3%B8%20%EA%B5%AC%EC%A1%B0%20%EC%9E%A1%EA%B8%B0.md)

[📁 02_Header 영역 완성하기](https://github.com/oiosu/Instagram_clone_coding/blob/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/02_Header%20%EC%98%81%EC%97%AD%20%EC%99%84%EC%84%B1%ED%95%98%EA%B8%B0.md)

[📁 03_Footer 영역 완성하기](https://github.com/oiosu/Instagram_clone_coding/blob/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/03_Footer%20%EC%98%81%EC%97%AD%20%EC%99%84%EC%84%B1%ED%95%98%EA%B8%B0.md)

### ✔ [인스타그램 기본 구조 & 가입 페이지 클론 코딩](https://github.com/oiosu/Instagram_clone_coding/tree/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83_%EC%BD%94%EB%93%9C)
![image](https://user-images.githubusercontent.com/99783474/221592900-5cf0ae1d-d39c-4ea2-bf52-cdedc08e0d00.png)

---

* get : url 에 표현을 해준다, ? 물음표 기호 분기, & 기호로 정보를 배치시켜서 전달, name="사용자가 입력한 값"
> get 경우에는 a 태그에 의해서 웹 페이지의 url를 변경하는 것과 동일하다. 
* post : 서버라는 곳에 action url 로 요청을 보내는 것 _ 데이터가 전달 

```html
<!-- 사용자와 소통할 수 있는 기본적인 태그 -->
    <form action="result.html" method="get">
        <!-- 보통  form 태그 안에 input 태그를 사용한다.-->
        <div>
            ID : <input name="id" type="text" />
        </div>
        <div>
            <!-- PW : <input name="password" type="text" /> -->
            <!-- <input name="password" type="text" /> -->
            <!-- 대신 password로 type을 지정해주면 비밀번호 작성 시 보이지 않는다.  -->
            PW : <input name="password" type="password" />
        </div>
        <input type="submit" value="login">
    </form>

```

---

* 버튼 형식에 대하여_ 차이점에 대해 잘 알아두기 
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

---

* 다중선택 
```html
 <div>
            모자 : <input type="checkbox" name="kind" value="hat">
            상의 : <input type="checkbox" name="kind" value="top">
            하의 : <input type="checkbox" name="kind" value="bottom">
            양말 : <input type="checkbox" name="kind" value="socks">
        </div>
```

* 반드시 하나의 값만 선택할 수 있도록 만들기 `radio`
```html
<div>
    남자 : <input type="radio" name="gender" value="man">
    여자 : <input type="radio" name="gender" value="woman">
</div>
```

---

* `label` 태그 

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

        <input type="submit" value="제출">
    </form>
```

---


* `form` 많이 사용하는 경우 

```html

<!-- input 태그는 긴 글을 받기에는 적절하지 않은 태그인 것 같다. -->
    <!-- 그럴 때 textarea 를 사용하면 된다. -->
    <form action="./result.html" method="get">
        <h1>게시글 작성</h1>
        <div>
            <label> 제목 : <br/>
                <input type="text" name="" id="">
            </label>
        </div>
        <div>
            <label> 내용 : <br /> 
                <!-- textarea 태그는 공백을 받는 태그이다. -->
                <!-- corls :  form에 맞춰서 글자가 30개가 들어간다. -->
                <!-- rows : 기본적으로 10줄 작성 , 그 이상 적어도 상관없다. -->
                <!-- 우측하단 으로 크기 조절 가능 하지만 사용자 UI를 고려하여  -->
                <!-- 사용자가 크기를 조절할 수 없도록 지정해주는 것이 일반적이다.  -->
                <!-- width: 300px  height: 200px resize: none; -->
                <textarea cols="30" rows="10" placeholder="내용을 입력해주세요"></textarea>
            </label>
        </div>

        <input type="submit" value="제출">
    </form>

```

---
* `i` 태그 
```html
  <button>
     <i class="fa-solid fa-heart-circle-plus"></i>
   </button>
```


