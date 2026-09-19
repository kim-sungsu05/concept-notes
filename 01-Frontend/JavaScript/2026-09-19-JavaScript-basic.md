# [JavaScript]

> **一行要約: HTMLを動的に制御する言語**

---

<br>

## 1.JavaScriptの概念
* **[JavaScript]**: 웹 페이지는 한 번 화면에 출력이 되면 그 다음에는 화면을 바꿀 수 없다. JavaScript가 이것을 가능하게 해준다. 사용자와 동적 상호작용도 가능하게 해준다.

```html
<!-- onclick 이라는 설정값을 넣어주면 자바스클립트 코드를 적을 수 있다 (클릭했을 때 자바스크립트 코드를 실행한다는 의미) -->
<body>
    <input type="button" value="name" onclick="
    document.querySelector('body').style.backgroundColor='black';
    document.querySelector('body').style.color='white';
    ">
</body>
```

<br>

## 2.コード例

```html
<!DOCTTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>JavaScript</title>
    </head>
    <body>
        <!-- JavaScript 문법을 html안에서 사용하기 위해서는 script 태그가 필요 -->
        <script>
            // 동적 언어이기 떄문에 출력시 2가 나옴
            document.write(1 + 1);
        </script>
        <!-- 반면 html로 1 + 1 연산을 하면 1 + 1이 그대로 출력됨 -->
        1 + 1
    </body>
</html>
```