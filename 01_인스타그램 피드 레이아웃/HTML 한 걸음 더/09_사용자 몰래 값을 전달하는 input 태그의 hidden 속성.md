# 09_사용자 몰래 값을 전달하는 input 태그의 hidden 속성

```
https://search.naver.com/search.naver?where=nexearch&sm=top_hty&fbm=1&ie=utf8&query=123
```

> 탐색해보기 



```html
    <form action="./result.html" method="get">
        <input type="text" name="text">
        <input type="hidden" name="where" value="top_search">
        <input type="submit" value="제출">
    </form>
```





```html
 <form action="./result.html" method="get">
        <input type="text" name="text">
        <input type="hidden" name="where" value="top_search">
        <input type="submit" value="제출">
    </form>

    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo illum aliquam officiis delectus accusantium? Quaerat dolorum doloribus ea libero earum! Mollitia voluptates saepe ex vitae dolorem, sed sunt! Numquam, ad.</p>

    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo illum aliquam officiis delectus accusantium? Quaerat dolorum doloribus ea libero earum! Mollitia voluptates saepe ex vitae dolorem, sed sunt! Numquam, ad.</p>

    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo illum aliquam officiis delectus accusantium? Quaerat dolorum doloribus ea libero earum! Mollitia voluptates saepe ex vitae dolorem, sed sunt! Numquam, ad.</p>


    <form action="./result.html" method="get">
        <input type="text" name="text">
        <input type="hidden" name="where" value="bottom_search">
        <input type="submit" value="제출">
    </form>
```

> * <input type="hidden" name="where" value="top_search">
> * <input type="hidden" name="where" value="bottom_search">

> 위치에 따라 많이 검색되는 부분을 분석하여 UI 를 구성할 때 참고할 수 도 있다. 

