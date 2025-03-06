# Noto Sans Korean for Web Developer

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE "License")
[![Release version](https://img.shields.io/github/release/devhaaana/noto-sans-korean.svg?label=Download&style=for-the-badge)](#release-files "Release Files")
[![Commits](https://img.shields.io/github/commit-activity/y/devhaaana/noto-sans-korean.svg?label=commits&style=for-the-badge)](https://github.com/devhaaana/radipy/commits "Commit History")
[![Last Commit](https://img.shields.io/github/last-commit/devhaaana/noto-sans-korean.svg?label=&style=for-the-badge&display_timestamp=committer)](https://github.com/devhaaana/radipy/pulse/monthly "Last Commit")

</div>

<div align="center">

[ENGLISH](/README.md)  ·  [한국어](/documents/README-KR.md)  ·  [日本語](/documents/README-JP.md)

</div>

`noto-sans-korean`은 웹 개발자를 위한 본고딕([Noto Sans Korean](https://fonts.google.com/noto/specimen/Noto+Sans+KR)) 웹 폰트입니다.

## 시작하기

### 설치

- **로컬** 설치
  ```console
  $ git clone https://github.com/devhaaana/noto-sans-korean.git
  $ cd noto-sans-korean
  ```
- 다운로드한 파일을 프로젝트의 원하는 경로에 넣어주세요.

#### 사용 방법: CSS

- 프로젝트의 메인 `.css` 파일 상단에 다음과 같이 **import** 하세요:

```css
@import("/noto-sans-korean/css/noto-sans-korean.css");
```

- body 또는 필요한 곳에 다음과 같이 폰트를 적용하세요:

```css
// OS 기본 폰트
// Mac OS: -apple-system, BlinkMacSystemFont
// Windows: Segoe UI
// Android: Roboto

body {
  font-family: "Noto Sans Korean", -apple-system, BlinkMacSystemFont, system-ui, "Helvetica Neue", "Segoe UI", Roboto, "Malgun Gothic", Helvetica, Arial, sans-serif;
}
```

##### 주의

- 폴더 경로를 변경할 경우 `css/noto-sans-korean.css` 파일에서 **경로를 변경**해야 합니다.
  - 기본 폴더 경로: `css/`, `fonts/`, `fonts/eot/`, `fonts/otf/`, `fonts/woff/`, `fonts/woff2/`

## 릴리스 파일

| 파일                 | 설명                                            |
| :------------------- | :---------------------------------------------- |
| [radipy-1.0.0.zip](https://github.com/devhaaana/noto-sans-korean/archive/refs/tags/v1.0.0.zip)    | v1.0.0의 전체 소스 코드가 포함된*ZIP* 파일    |
| [radipy-1.0.0.tar.gz](https://github.com/devhaaana/noto-sans-korean/archive/refs/tags/v1.0.0.tar.gz) | v1.0.0의 전체 소스 코드가 포함된*TAR.GZ* 파일 |
