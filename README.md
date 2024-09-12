# 모노플렉스KR Wide Nerd

[배포처 바로가기](https://github.com/y-kim/monoplex)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Monoplex KR Wide Nerd`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 100;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Thin.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 200;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraLight.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 600;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-SemiBold.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-Bold.ttf') format('truetype');
}
@font-face {
    font-family: 'Monoplex KR Wide Nerd';
    font-weight: 800;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/MonoplexKRWideNerd-ExtraBold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/subsets/MonoplexKRWideNerd-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/MonoplexKRWideNerd/subsets/MonoplexKRWideNerd-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Monoplex KR Wide Nerd", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
Copyright (c) 2021, Kim Yangsu with Reserved Font Name "Monoplex" and "Monoplex KR" 
 
The Monoplex generate script (https://github.com/y-kim/monoplex) is licensed under the MIT License. 
It is derived from the PlemolJP generate script (https://github.com/yuru7/PlemolJP) which is licensed under the MIT License. 
And Monoplex Font Software is licensed under the SIL Open Font License v1.1.
```
