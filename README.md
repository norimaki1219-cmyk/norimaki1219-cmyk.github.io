# norimaki1219-cmyk.github.io

GitHub Pages のドメイン直下（`https://norimaki1219-cmyk.github.io/`）に置くファイル用のリポジトリです。

| ファイル | 内容 |
|---|---|
| `robots.txt` | 検索エンジン向けの設定。ドメイン直下にしか置けないため、このリポジトリで管理する。このドメインの下の全サイト（`/eda/`、`/kasane/` など）に効く |
| `.nojekyll` | GitHub Pages の Jekyll 処理を止める。これがないと、この README がトップページとして表示されてしまう |

- トップページ（`index.html`）は置いていない（直下は「見つからない」のまま）。各サイトは `/eda/`・`/kasane/` など、それぞれのリポジトリで公開している。
- サイトマップを持つサイトが増えたら、`robots.txt` に `Sitemap:` 行を足す。
