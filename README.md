<div align="center">

[![Banner](./images/banner.svg)](#readme)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE "License")
[![Release version](https://img.shields.io/github/release/devhaaana/noto-sans-korean.svg?label=Download&style=for-the-badge)](#release-files "Release Files")
[![Commits](https://img.shields.io/github/commit-activity/y/devhaaana/noto-sans-korean.svg?label=commits&style=for-the-badge)](https://github.com/devhaaana/radipy/commits "Commit History")
[![Last Commit](https://img.shields.io/github/last-commit/devhaaana/noto-sans-korean.svg?label=&style=for-the-badge&display_timestamp=committer)](https://github.com/devhaaana/radipy/pulse/monthly "Last Commit")

</div>

<div align="center">

[ENGLISH](/README.md)  ·  [한국어](/documents/README-KR.md)  ·  [日本語](/documents/README-JP.md)

</div>

`noto-sans-korean` is a [Noto Sans Korean](https://fonts.google.com/noto/specimen/Noto+Sans+KR) web font for web developers.

## Getting Started

### Installation

- You can install it **locally**:
  ```console
  $ git clone https://github.com/devhaaana/noto-sans-korean.git
  $ cd noto-sans-korean
  ```
- Place the downloaded files in your preferred project directory.

### Usage: CSS

- **Import** the stylesheet at the top of your main `.css` file:

```css
@import("/noto-sans-korean/css/noto-sans-korean.css");
```

- Apply the font to the `body` or any necessary elements:

```css
// Default OS fonts
// Mac OS: -apple-system, BlinkMacSystemFont
// Windows: Segoe UI
// Android: Roboto

body {
  font-family: "Noto Sans Korean", -apple-system, BlinkMacSystemFont, system-ui, "Helvetica Neue", "Segoe UI", Roboto, "Malgun Gothic", Helvetica, Arial, sans-serif;
}
```

### Caution

- If you change the folder path, make sure to **update the paths** in `css/noto-sans-korean.css`.
  - Default folder structure: `css/`, `fonts/`, `fonts/eot/`, `fonts/otf/`, `fonts/woff/`, `fonts/woff2/`

## Release Files

| File                 | Description                                                 |
| :------------------- | :---------------------------------------------------------- |
| [v1.0.0.zip](https://github.com/devhaaana/noto-sans-korean/archive/refs/tags/v1.0.0.zip)    | A*ZIP* file containing the full source code of v1.0.0.    |
| [v1.0.0.tar.gz](https://github.com/devhaaana/noto-sans-korean/archive/refs/tags/v1.0.0.tar.gz) | A*TAR.GZ* file containing the full source code of v1.0.0. |
