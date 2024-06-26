# 충북대직지체

[배포처 바로가기](https://www.chungbuk.ac.kr/site/pr/sub.do?key=1827)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `CBNU JIKJI`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/CBNUJIKJI.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/CBNUJIKJI.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'CBNU JIKJI';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/CBNUJIKJI.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/CBNUJIKJI.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/CBNUJIKJI.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/CBNUJIKJI.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/subsets/CBNUJIKJI-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/CBNUJIKJI/subsets/CBNUJIKJI-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "CBNU JIKJI", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
사용 금지 규정 
본 항은 사용 금지 규정으로 충북대직지체가 왜곡되거나 변경되는 등의 이미지 손상이 발생하지 않도록 세심한 주의가 요구된다. 
본 항의 예시는 잘못 적용된 경우를 제시한 것으로 이를 참고하여 충북대직지체의 왜곡 및 변형이 발생하지 않도록 철저히 관리한다. 

공공누리의 제 1유형 
제 1유형 : 출처표시 (공공저작물의 자유이용) 
- 출처표시 
- 상업적, 비상업적 이용가능 
- 변형 등 2차적 저작물 작성 가능 
* 주의 : 기관사용자는 공공누리 유형마크를 다운로드 후 사용시 지정된 유형마크 파일명 변경을 금지 
공공누리 마크 다운받기 

공공누리의 제 1유형 개별조건 
출처표시 
저작물의 출처를 표시해야 됩니다. 

이용자는 공공저작물을 이용할 경우, 다음과 같이 출처 또는 저작권자를 표시해야 합니다. 
ex) "본 저작물은 'OOO(기관명)'에서 'OO년'작성하여 공공누리 제O유형으로 개방한 '저작물명(작성자:OOO)'을 이용하였으며, 
해당 저작물은 'OOO(기관명),OOO(홈페이지주소)'에서 무료로 다운받으실 수 있습니다." 

위 내용은 예시이므로 작성연도 및 해당 기관명과 홈페이지 주소, 작성자명 기입 
온라인에서 출처 웹사이트에 대한 하이퍼링크를 제공하는 것이 가능한 경우에는 링크를 제공하여야 합니다. 
이용자는 공공기관이 이용자를 후원한다거나 공공기관과 이용자가 특수한 관계에 있는 것처럼 제3자가 오인하게 하는 표시를 해서는 안됩니다. 

본 저작물은 '충북대학교'에서 '2020년'작성하여 공공누리 제1유형으로 개방한 '충북대직지체(작성자:충북대학교)'을 이용하였으며, 해당 저작물은 '충북대학교, https://www.chungbuk.ac.kr/site/pr/sub.do?key=1798'에서 무료로 다운받으실 수 있습니다.
```
