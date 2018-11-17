# Colorfi Preview Theme

A custom Markdown preview theme for [Inkdrop](https://www.inkdrop.info/).

デフォルトの Github テーマでは日本語部分がメイリオになります。そうすると斜体が表示されないため日本語環境向けにフォント設定をしました。

日本語文字部分に対してのみ、  
源ノ角ゴシック JP > 游ゴシック (Windows の場合は游ゴシック Medium) >  ヒラギノ角ゴ Pro W3 > メイリオ  
の優先順で適用される想定です。

また、 h1 要素と h2 要素の区別が付きやすいように下線を追加しています。

コードブロックの文字色が美しい [Colorfi Preview Theme](https://github.com/laurenhamel/inkdrop-colorfi-preview-theme) からフォークさせていただきました。


## Install

```
ipm install colorfi-for-japanese-preview
```

## Theming code blocks

Highlighting code blocks is built with [CodeMirror](https://codemirror.net/demo/theme.html), and CSS selectors for styling code blocks are compatible with it.
CSS selectors always start with `cm-`.
You can easily import styles from [CodeMirror's theme](https://github.com/codemirror/CodeMirror/tree/master/theme).
