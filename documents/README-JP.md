# Noto Sans Korean for Web Developer

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE "License")

<!-- [![Release version](https://img.shields.io/github/release/devhaaana/noto-sans-korean.svg?label=Download&style=for-the-badge)](#release-files "Release Files") -->

[![Commits](https://img.shields.io/github/commit-activity/y/devhaaana/noto-sans-korean.svg?label=commits&style=for-the-badge)](https://github.com/devhaaana/radipy/commits "Commit History")
[![Last Commit](https://img.shields.io/github/last-commit/devhaaana/noto-sans-korean.svg?label=&style=for-the-badge&display_timestamp=committer)](https://github.com/devhaaana/radipy/pulse/monthly "Last Commit")

</div>

<div align="center">

[ENGLISH](/README.md)  ·  [한국어](/documents/README-KR.md)  ·  [日本語](/documents/README-JP.md)

</div>

`noto-sans-korean`は、ウェブ開発者のための[Noto Sans Korean](https://fonts.google.com/noto/specimen/Noto+Sans+KR)ウェブフォントです。

## はじめに

### インストール

- **ローカル**にインストールする方法:
  ```console
  $ git clone https://github.com/devhaaana/noto-sans-korean.git
  $ cd noto-sans-korean
  ```
- ダウンロードしたファイルをプロジェクトの任意のディレクトリに配置してください。

#### 使用方法: CSS

- スタイルシートを**インポート** するには、メインの `.css` ファイルの上部に次のコードを追加してください:

```css
@import("/noto-sans-korean/css/noto-sans-korean.css");
```

- body 要素または必要な要素にフォントを適用してください:

```css
// デフォルトのOSフォント
// Mac OS: -apple-system, BlinkMacSystemFont
// Windows: Segoe UI
// Android: Roboto

body {
  font-family: "Noto Sans Korean", -apple-system, BlinkMacSystemFont, system-ui, "Helvetica Neue", "Segoe UI", Roboto, "Malgun Gothic", Helvetica, Arial, sans-serif;
}
```

##### 注意事項

- フォルダのパスを変更する場合は、css/noto-sans-korean.css 内のパスを更新する必要があります。
  - デフォルトのフォルダ構成: `css/`, `fonts/`, `fonts/eot/`, `fonts/otf/`, `fonts/woff/`, `fonts/woff2/`

## リリースファイル

| ファイル             | 説明                                                           |
| :------------------- | :------------------------------------------------------------- |
| [radipy-1.0.0.zip]()    | バージョン1.0.0の完全なソースコードを含む*ZIP* ファイル。    |
| [radipy-1.0.0.tar.gz]() | バージョン1.0.0の完全なソースコードを含む*TAR.GZ* ファイル。 |
