# π μ΄ κ°μλ₯Ό μ ννκ³  κ³΅λΆνλ μ΄μ  
κ·Έλμ μκ³  μμλ HTML/CSS κ°λμ μΈ λΆλΆλ€μ λ³΅μ΅νλ μκ°μ κ°μ§κ³  μΆμ λ§μμ μ΄ κ°μλ₯Ό λ£κ² λμμ΅λλ€. <br>
6κ°μ νμ€ν κ°μ μ΄ν νλ‘ νΈμλ κ°λ°μκ° λκΈ°μν μ­λλ€μ μ°Ύμλ³΄λ©° HTML, CSS κ°λμ μΈ λΆλΆλ€λ μ€μνλ€λ κ²μ λκΌκ³ , <br>
μκ³  μλ λ΄μ©λ€λ κ³μ μμ§ μκ³ μ κ°μλ€μ λ€μΌλ©° κ³΅λΆ λ΄μ©μ νμνμμ΅λλ€. <br>
λν κ·Έμν¨κ» ν΄λ‘ μ½λ©μ μ΄λ»κ² νλ©΄ μν  μ μμμ§μ λν κ³ λ―Όμ νκ³  μμΌλ©°, λΌμ΄νΈλ ν ν¬λ₯Ό ν΅ν΄ κ·Έλμ λ°°μ λ HTML, CSS, JS κ°λμ  νμ©νμ¬ <br>
ννμ΄μ§λ₯Ό μ§μ  λ§λ€μ΄ λ³΄λ νλ‘μ νΈλ₯Ό μ§ννκ³  μμ΅λλ€. 


---



# Instagram_clone_coding
[π 01_κΈ°λ³Έκ΅¬μ‘°μ‘κΈ°](https://github.com/oiosu/Instagram_clone_coding/blob/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/01_%EA%B8%B0%EB%B3%B8%20%EA%B5%AC%EC%A1%B0%20%EC%9E%A1%EA%B8%B0.md)

[π 02_Header μμ­ μμ±νκΈ°](https://github.com/oiosu/Instagram_clone_coding/blob/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/02_Header%20%EC%98%81%EC%97%AD%20%EC%99%84%EC%84%B1%ED%95%98%EA%B8%B0.md)

[π 03_Footer μμ­ μμ±νκΈ°](https://github.com/oiosu/Instagram_clone_coding/blob/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/03_Footer%20%EC%98%81%EC%97%AD%20%EC%99%84%EC%84%B1%ED%95%98%EA%B8%B0.md)

### β [μΈμ€νκ·Έλ¨ κΈ°λ³Έ κ΅¬μ‘° & κ°μ νμ΄μ§ ν΄λ‘  μ½λ©](https://github.com/oiosu/Instagram_clone_coding/tree/master/01_%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83/%EC%9D%B8%EC%8A%A4%ED%83%80%EA%B7%B8%EB%9E%A8%20%ED%94%BC%EB%93%9C%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83_%EC%BD%94%EB%93%9C)
![image](https://user-images.githubusercontent.com/99783474/221592900-5cf0ae1d-d39c-4ea2-bf52-cdedc08e0d00.png)

---

* get : url μ ννμ ν΄μ€λ€, ? λ¬Όμν κΈ°νΈ λΆκΈ°, & κΈ°νΈλ‘ μ λ³΄λ₯Ό λ°°μΉμμΌμ μ λ¬, name="μ¬μ©μκ° μλ ₯ν κ°"
> get κ²½μ°μλ a νκ·Έμ μν΄μ μΉ νμ΄μ§μ urlλ₯Ό λ³κ²½νλ κ²κ³Ό λμΌνλ€. 
* post : μλ²λΌλ κ³³μ action url λ‘ μμ²­μ λ³΄λ΄λ κ² _ λ°μ΄ν°κ° μ λ¬ 

```html
<!-- μ¬μ©μμ μν΅ν  μ μλ κΈ°λ³Έμ μΈ νκ·Έ -->
    <form action="result.html" method="get">
        <!-- λ³΄ν΅  form νκ·Έ μμ input νκ·Έλ₯Ό μ¬μ©νλ€.-->
        <div>
            ID : <input name="id" type="text" />
        </div>
        <div>
            <!-- PW : <input name="password" type="text" /> -->
            <!-- <input name="password" type="text" /> -->
            <!-- λμ  passwordλ‘ typeμ μ§μ ν΄μ£Όλ©΄ λΉλ°λ²νΈ μμ± μ λ³΄μ΄μ§ μλλ€.  -->
            PW : <input name="password" type="password" />
        </div>
        <input type="submit" value="login">
    </form>

```

---

* λ²νΌ νμμ λνμ¬_ μ°¨μ΄μ μ λν΄ μ μμλκΈ° 
```html
 <!--λ€μ 4κ°λ κ°μ λ‘κ·ΈμΈ λ²νΌ νμμΌλ‘ λ³΄μ¬μ§λ€.  -->
    <!-- submitμ λ²νΌ νμ -->
    <!-- 1. form μ μΆλ¨ -->
    <input type="submit" value="λ‘κ·ΈμΈ"/>
    <!-- 2. form μ μΆμλ¨ -->
    <input type="button" value="λ‘κ·ΈμΈ"> 
    <!-- 3. form μ μΆλ¨  -->
    <button type="submit">λ‘κ·ΈμΈ</button>
    <!-- 3. form μ μΆλ¨  -->
    <button>λ‘κ·ΈμΈ</button>
```

---

* λ€μ€μ ν 
```html
 <div>
            λͺ¨μ : <input type="checkbox" name="kind" value="hat">
            μμ : <input type="checkbox" name="kind" value="top">
            νμ : <input type="checkbox" name="kind" value="bottom">
            μλ§ : <input type="checkbox" name="kind" value="socks">
        </div>
```

* λ°λμ νλμ κ°λ§ μ νν  μ μλλ‘ λ§λ€κΈ° `radio`
```html
<div>
    λ¨μ : <input type="radio" name="gender" value="man">
    μ¬μ : <input type="radio" name="gender" value="woman">
</div>
```

---

* `label` νκ·Έ 

```html 
  <!-- label νκ·Έ -->
        <div>
            <!-- 1. label νκ·Έμ λν μ€λͺμ inputλ‘ ν  μ μλ€. -->
            <!-- : label νκ·Έ μμ inputνκ·Έ  -->
            <label>λͺ¨μ : 
                <input type="checkbox" name="kind" value="hat">
            </label>

            <!-- 2. label μμ±μ for μΆκ° -->
            <!-- label for top μμ΄λμ λμΌν κ°μ κ°μ§ μμ±μ labelμ λν μ€λͺμ΄ λ΄κΈ΄ κ²  -->
            <label for="top"> μμ : </label>
            <input type="top" type="checkbox" name="kind" value="top">
        </div>

        <!-- label νκ·Έ μ λ¦¬ -->
        <div>
            <label> μ΄λ©μΌ
                <input type="email" name="" id="">
            </label>
        </div>

        <div>
            <label for=""> λΉλ°λ²νΈ
                <input type="password" name="" id="">
            </label>
        </div>

        <input type="submit" value="μ μΆ">
    </form>
```

---


* `form` λ§μ΄ μ¬μ©νλ κ²½μ° 

```html

<!-- input νκ·Έλ κΈ΄ κΈμ λ°κΈ°μλ μ μ νμ§ μμ νκ·ΈμΈ κ² κ°λ€. -->
    <!-- κ·Έλ΄ λ textarea λ₯Ό μ¬μ©νλ©΄ λλ€. -->
    <form action="./result.html" method="get">
        <h1>κ²μκΈ μμ±</h1>
        <div>
            <label> μ λͺ© : <br/>
                <input type="text" name="" id="">
            </label>
        </div>
        <div>
            <label> λ΄μ© : <br /> 
                <!-- textarea νκ·Έλ κ³΅λ°±μ λ°λ νκ·Έμ΄λ€. -->
                <!-- corls :  formμ λ§μΆ°μ κΈμκ° 30κ°κ° λ€μ΄κ°λ€. -->
                <!-- rows : κΈ°λ³Έμ μΌλ‘ 10μ€ μμ± , κ·Έ μ΄μ μ μ΄λ μκ΄μλ€. -->
                <!-- μ°μΈ‘νλ¨ μΌλ‘ ν¬κΈ° μ‘°μ  κ°λ₯ νμ§λ§ μ¬μ©μ UIλ₯Ό κ³ λ €νμ¬  -->
                <!-- μ¬μ©μκ° ν¬κΈ°λ₯Ό μ‘°μ ν  μ μλλ‘ μ§μ ν΄μ£Όλ κ²μ΄ μΌλ°μ μ΄λ€.  -->
                <!-- width: 300px  height: 200px resize: none; -->
                <textarea cols="30" rows="10" placeholder="λ΄μ©μ μλ ₯ν΄μ£ΌμΈμ"></textarea>
            </label>
        </div>

        <input type="submit" value="μ μΆ">
    </form>

```

---
* `i` νκ·Έ 
```html
  <button>
     <i class="fa-solid fa-heart-circle-plus"></i>
   </button>
```


