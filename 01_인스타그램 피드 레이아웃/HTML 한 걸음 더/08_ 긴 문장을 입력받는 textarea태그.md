# 08_ 긴 문장을 입력받는 textarea태그

```html
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

