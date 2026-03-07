# Public Site Publish Guide

## Purpose
この公開サイトは、事業者確認（Business Verification）および顧客向けサービス概要の提示のみを目的としています。

## Recommended Publishing Options
- GitLab Pages
- GitHub Pages

## Security and Repository Policy
- 実装リポジトリ（アプリ本体・API内部実装・運用スクリプト）は非公開（private）のまま維持してください。
- 公開対象は `public_site/` 配下のファイルのみに限定してください。

## Files to Publish
- `public_site/index.html`
- `public_site/tokushoho.html`
- `public_site/styles.css`
- `public_site/README_publish.md`

## Stripe Business Verification
`特定商取引法に基づく表記` ページ（`public_site/tokushoho.html`）を公開し、その公開URLをStripeのbusiness verification提出URLとして使用してください。

## Minimal Publish Flow
1. `public_site/` 配下のみを公開用リポジトリまたは Pages 用ブランチに配置する。
2. GitLab Pages または GitHub Pages を有効化する。
3. 公開URLで表示内容を確認し、事業者確認・顧客案内に利用する。
