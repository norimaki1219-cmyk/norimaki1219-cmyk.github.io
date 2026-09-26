# norimaki1219-cmyk.github.io

GitHub Pages のドメイン直下（`https://norimaki1219-cmyk.github.io/`）に置くファイル用のリポジトリです。

| ファイル | 内容 |
|---|---|
| `robots.txt` | 検索エンジン向けの設定。ドメイン直下にしか置けないため、このリポジトリで管理する。このドメインの下の全サイト（`/eda/`、`/kasane/` など）に効く |
| `index.html` | ドメイン直下のトップページ（サイト一覧）。EDA と KASANE へ案内する。どちらかへ自動で転送はしない |
| `.nojekyll` | GitHub Pages の Jekyll 処理を止める |

- 各サイトは `/eda/`・`/kasane/` など、それぞれのリポジトリで公開している。サイトが増えたら `index.html` にカードを足す。
- EDA のロゴ・アイコンは `/eda/` のものを参照している（EDA 側でファイル名を変えたらここも直す）。
- サイトマップを持つサイトが増えたら、`robots.txt` に `Sitemap:` 行を足す。
