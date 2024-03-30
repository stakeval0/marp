# marp-style
[rnd195](https://github.com/rnd195)さんの[my-marp-themes](https://github.com/rnd195/my-marp-themes)の`beam`からインスパイアされて作成しています。

スライドを作る上で便利な複数のクラスを追加実装しています。

raw link: https://raw.githubusercontent.com/stakeval0/marp-style/main/beamer.css

## クラス

想定している使い方は[`markdown.json`](./markdown.json)を参照。

### Marp class

- `title`: タイトル用
- `section`: 章を区切りたいとき用
  - デフォルトだとスライド左半分の長さだが、文字が増えると内容に適用して横に大きくなる。これはPowerPointじゃできない:raised_hands:

### CSS class

- `colimg`: 左に箇条書き、右に画像の配置を想定
- `columns`: 横方向並列化。枠線、h4によるタイトル付
- `row`: 縦方向並列化。枠線、h4によるタイトル付
- `parallel`: 横方向並列化
- `flex`: 横方向にflex化
- `colorbox`: 色と枠線付き強調ブロック要素
- `arraybox`: ブロック要素を並べていくことが目的
- `li.arrow`: 箇条書きのbulletを矢印`➡`にする

## ローカルでスタイルを適用する場合

必要に応じて`.vscode`をMarkdownファイルのあるディレクトリに配置してください。

```
.
├── .vscode <-copied!
├── slide.md
└── marp-style
    ├── .vscode <-original
    └── beamer.css
```
