# 홈페이지 메인 화면 Cloning
--

기본 골격
```html
<body>
    <nav>
        메뉴 바 등의 영역
    </nav>
    <header>
        이벤트 링크 영역
    </header>
    <main>
        메인 정보 영역
    </main>
    <footer>
        하단 정보 영역
    </footer>
</body>
```
semantic한 markup 작성을 위해 div, span은 최대한 지양한다. 각 태그가 가진 의미에 알맞은 markup 작성을 추구한다.

\<figure\> 태그는 독립적인 콘텐츠를 표현. \<figcaption\>이 내부에서 \<img\> 요소의 설명이 보이게한다.