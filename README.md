# ことばパレット

- AI画像プロンプト単語帳 -

AI画像生成向けのプロンプト単語を検索・管理・組み合わせできるWebアプリです。

## 公開サイト

GitHub Pages:
https://pomcreate99.github.io/kotoba-palette/

## リポジトリ

https://github.com/pomcreate99/kotoba-palette

## 主な機能

- 日本語・英語タグの検索
- SFW / NSFW の分類
- Positive / Negative の分類
- カテゴリ・サブカテゴリによる絞り込み
- お気に入り、カスタムタグ、コピー履歴
- レシピ・ランダム生成
- 更新履歴、フィードバック、関連リンク

## データ方針

既存の監査済みタグデータをベースに、タグの意味を推測して削除・統合することは行いません。
IDや既存データの互換性をできるだけ維持し、公開用設定のみGitHub Pages向けに整理しています。

## 開発

```bash
pnpm install
pnpm check
pnpm test
pnpm exec vite build
```

GitHub Actions は `main` へのpush時に型チェック、テスト、Viteビルドを実行し、成功した場合にGitHub Pagesへ公開します。
