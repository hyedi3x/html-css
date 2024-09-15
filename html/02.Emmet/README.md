## 🤖 Emmet 사용 설명서
#### 🔎 Emmet은 코드 타이핑을 최소화하기 위한 html/css 자동 완성 확장 기능이다. 
<br>

⚙️ `! + tab키` : 간단하고 빠르게 html 기본 구조를 생성할 수 있다. <br>
⚙️ `> 자식노드` : **>** 를 사용하여 자식 요소를 생성할 수 있다. 
```html
<!-- 자식노드 자동 완성 | div>ul>li & tab키 -->
<div>
    <ul>
        <li></li>
    </ul>
</div>
```
<br>

⚙️ `+ 형제 노드` : **+** 를 사용하여 한 요소와 같은 단계에 위치한(형제 노드) 요소를 생성할 수 있다. 
```html
<!-- 형제 노드 자동 완성 | div>ol+ul+div & tab키 -->
<div>
    <ol></ol>
    <ul></ul>
    <div></div>
</div>
```
<br>

⚙️ `* 요소 반복` : *를 사용하여 요소를 반복해서 생성할 수 있다. 
```html
<!-- 반복 자동완성 | div>ul>li*3 & tab키 -->
<div>
    <ul>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</div>
```
<br>

⚙️ `# 아이디 생성 태그` : **#** 를 사용하여 id를 갖는 요소를 생성할 수 있다. (기본이 div 태그로 구성되어 있다.)
```html
<!-- # 아이디 자동완성 | #아이디명 / span#아이디명 -->
<span id="item"></span>
<div id="item"></div>
```
<br>

⚙️ `. 클래스 생성 태그` : **.** 를 사용하여 CSS class를 갖는 요소를 생성할 수 있다. (기본이 div 태그로 구성되어 있다.)
```html
<!-- . 클래스 자동완성 | .클래스명 / span.클래스명 -->
<span class="title"></span>
<div class="title"></div>
```
<br>

⚙️ `{ } 텍스트 입력` : **{ }** 를 사용하여 요소 안에 내용을 갖는 요소를 생성한다.
```html
<!-- {} 텍스트 자동완성 | 태그.클래스명{텍스트} - tab키 / 태그#아이디명{텍스트} - tab키 -->
<p class="container">Hello World~!</p>
<p id="font">Hello World~!</p>
```
<br>

---
<br>

💡 **Emmet 참조 사이트** <br>
https://docs.emmet.io/abbreviations/syntax/