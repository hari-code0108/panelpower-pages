# PanelPower public pages

GitHub Pagesで公開する静的ファイル一式です。リポジトリの公開元をルートに設定すると、次のパスで表示されます。

- `/privacy/`
- `/terms/`
- `/support/`

HTML内のページリンクとCSS参照は相対パスです。プロジェクトサイト、ユーザーサイト、独自ドメインのいずれでも、ファイル構成を保ったまま利用できます。

## 構成

```text
.
├── .nojekyll
├── index.html
├── assets/
│   └── style.css
├── privacy/
│   └── index.html
├── terms/
│   └── index.html
└── support/
    └── index.html
```
