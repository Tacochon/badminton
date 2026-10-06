# ライター ポートフォリオサイト

ライターとしての自己紹介・実績・お問い合わせをまとめた1ページのホームページです。
HTML と CSS だけで動くので、`index.html` をブラウザで開けばすぐに確認できます。

## 編集する場所

| 変えたいもの | ファイル / 場所 |
| --- | --- |
| 名前・キャッチコピー・プロフィール文 | `index.html` のヒーロー / プロフィール |
| 実績（記事タイトル・掲載先・リンク） | `index.html` の `#works` 内の `work-card`（`href="#"` を記事URLに） |
| お仕事内容・料金の案内 | `index.html` の `#services` |
| メールアドレス・SNS | `index.html` の `#contact` |
| プロフィール写真 | `images/profile.jpg` を置き、`about-photo` 内を `<img>` に差し替え |
| サイトの色 | `style.css` 冒頭の `:root` |

※ 名前・経歴・実績はすべてサンプルです。

## 公開方法（GitHub Pages）

リポジトリの Settings → Pages で、Branch を公開したいブランチ・`/ (root)` に設定すると
`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。
