# 05_form 태그에서의 드랍다운(dropdown)

```html
    <form action="./result.html" method="get">
        <select name="color" id="">
            <option value="">빨간색</option>
            <option value="">파랑색</option>
            <option value="">노랑색</option>
        </select>
        <input type="submit" value="제출">
    </form>
```

![image-20230206203050959](../imges/05_form 태그에서의 드랍다운(dropdown)/image-20230206203050959.png)

> 제출 버튼을 눌러도 정보가 전달이 되고 있지 않음을 알 수 있다. 



```html
    <form action="./result.html" method="get">
        <select name="color" id="">
            <option value="red">빨간색</option>
            <option value="blue">파랑색</option>
            <option value="yellow">노랑색</option>
        </select>
        <input type="submit" value="제출">
    </form>
```

![image-20230206203317603](../imges/05_form 태그에서의 드랍다운(dropdown)/image-20230206203317603.png)

> 서버에 대해 더 많이 공부하기 



##### 사용자가 만약 다중 선택하고 싶다면? 

* `select` 에 `multiple`속성 작성하기 

```html
 <select name="color" multiple>
```

