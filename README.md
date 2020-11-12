# Web Study

## 1. html, css 작성

[참고 페이지](https://heropcode.github.io/GitHub-Responsive/)

### 과제 진행하면서 새로 알게 된 개념 정리

#### 뷰포트(viewport)

HTML5에서 소개된 뷰포트 <meta> 태그를 사용하면 모바일 기기에서 실제 렌더링되는 영역과 뷰포트의 크기를 조절할 수 있다. 또한 줌 레벨도 조정할 수 있다. 아래는 가장 일반적으로 사용되는 설정이다.

<meta name="viewport" content="width=device-width, initial-scale=1.0">
- `width=device-width` : 페이지의 너비를 기기의 스크린 너비로 설정. 즉, 렌더링 영역을 기기의 뷰포트의 크기와 동일하게 설정한다.
- `initial-scale=1.0` : 처음 페이지 로딩 시 확대/축소가 되지 않은 원래 크기를 사용하도록 설정.

#### 그 외 소소한 정보 정리

여러 링크를 리스트형태로 보여줄 때, 

1. 목록 앞의 마커 제거
2. 하이퍼링크 밑줄 제거

```css
li {
	list-style: none;  // 1. 목록 앞의 마커 제거
}

a {
	text-decoration: none;  // 2. 하이퍼링크 밑줄 제거
}
```

