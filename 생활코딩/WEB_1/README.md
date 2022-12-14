# WEB 1 필기

<a href="https://ofcourse.kr/html-course/HTML-%EC%9E%85%EB%AC%B8">HTML 문법 사이트</a>
   
**10, 16, 17강 자주보기!**

**태그(HTML의 기본문법)**: 옷에 붙어있는 태그를 생각해보면 옷을 설명해주고 있다. 이처럼 HTML의 태그도 텍스트를 설명해주는 것과 같다

▶️ <?> 태그의 시작

▶️ </?> 태그의 끝

**속성 (attribute)**: 태그의 이름만으로는 정보가 부족할 때 속성을 통해 더 많은 의미를 부가할 수 있다 (위치는 상관없다)

**parent, child**: 포함하고 있는 태그(parent) 포함된 태그(child)
```
<parent>
  <child></child>
<parent>
 ```

---
**!doctype**: 이 문서는 ???이다
```
<!doctype html> 이 문서는 html이다
```

**html (최고위층태그)**: 꼭 고위직 태그 위에 써줘야 한다
```
<html>
```

**head (고위직태그)**: 문서의 머리를 나타내는 태그 (내부에 들어가는 태그들: title, meta, link, style, script)
```
<head></head>
```

**body (고위직태그)**: 문서의 몸통을 나타내는 태그 (내부에 들어가는 태그들:br, p, b, i, h1, a, img, table, div, span, ul, il, form)
```
<body></body>
```

**title**: 웹 페이지의 제목을 나타내는 태그 (웹 페이지 본문에는 보이지 않으며, 브라우저의 탭에서 확인 가능)
```
<title></title>
```

**meta**: 웹 페이지의 보이지 않는 정보를 제공하는데 쓰이는 태그
```
<meta charset="utf-8">
```

**strong**: 글자를 진하게 표시할 수 있다
```
<strong></strong>
```

**u (underline)**: 글자에 밑줄을 칠 수 있다
```
<u></u>
```

**h1 ~ 6**: 글자를 제목으로 지정해준다 숫자가 올라갈 수록 더 작아지는 제목이 된다
```
<h1 ~ 6></h1 ~ 6>
```

**br**: 줄바꿈을 하는 태그이다.두번을 하면 두번 줄바꿈이 된다 (줄바꿈이라는 시각적의미만을 가지고 있기 때문에 닫아줄 필요가 없다)
```
<br>
```

**p (paragraph)**: 어디서부터 어디까지 한 단락이라고 알려주는 태그이다 (한문단으로 묶임) ▶️ CSS로 태그와 태그 사이의 여백(마진)을 줄 수 있다
```
<p></p>
```

**img**: 이미지를 넣는 태그 (진행하고있는 프로젝트 파일에 저장해야함)
```
<img src="이미지이름.jpg" width="숫자로 사진크기 설정">
```

**li**: 목록을 만드는 태그 (이 태그는 단독으로 쓰이지 않으며 ul, ol 태그 내부에 들어간다)
```
<li></li>
```

**ul (unordered list)**: 순서없이 모양으로 목록을 만든다
```
<ul>
  <li>목록1</li>
  <li>목록1</li>
</ul>
```

**ol (ordered list)**: 번호를 메겨 순서가 있는 목록을 만든다
```
<ol>
  <li>목록1</li>
  <li>목록2</li>
</ol>
```
**a**: 글자에 링크를 넣을 수 있다
```
<a href="링크주소" target="_blank(다른탭에 링크실행)" title="클릭하기 전에 무슨 정보인지 알려주는 것"></a>
```
