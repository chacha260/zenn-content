# zenn-content

Zenn の記事を管理するリポジトリです。[Zenn CLI](https://zenn.dev/zenn/articles/zenn-cli-guide) を使っています。

- 記事は `articles/` に Markdown で置きます。ファイル名が記事の URL の一部(slug)になります。
- Zenn と連携したブランチにプッシュすると、記事が反映されます。
- front matter の `published: false` の記事は下書きのままです。公開するときに `true` にします。
- 画像は `images/` に置き、記事からは `/images/ファイル名` で参照します。

## 手元でのプレビュー

```bash
npm install
npx zenn preview
```
