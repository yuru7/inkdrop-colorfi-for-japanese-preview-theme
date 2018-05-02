# Colorfi Preview Theme

A custom Markdown preview theme for [Inkdrop](https://www.inkdrop.info/).

デフォルトの Github テーマでは日本語部分がメイリオになってしまい斜体が表示されないため、日本語環境向けのフォント設定を設定してみました。

コードブロックの文字色が美しい [Colorfi Preview Theme](https://github.com/laurenhamel/inkdrop-colorfi-preview-theme) からフォークさせていただいています。

日本語文字部分に対してのみ、Windows では游ゴシック Medium, Mac では通常の游ゴシックが適用される想定ではいますが、Windows でしか動作確認はできていません。

## Theming code blocks

Highlighting code blocks is built with [CodeMirror](https://codemirror.net/demo/theme.html), and CSS selectors for styling code blocks are compatible with it.
CSS selectors always start with `cm-`.
You can easily import styles from [CodeMirror's theme](https://github.com/codemirror/CodeMirror/tree/master/theme).
