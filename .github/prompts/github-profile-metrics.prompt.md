---
description: "lowlighter/metrics@latest を使った GitHub プロフィール README と Actions 設定を日本語で作成する"
name: "GitHub Profile Metrics 作成"
argument-hint: "GitHubユーザー名、見せたい指標、デザイン方針（例: ミニマル/ポップ）"
agent: "agent"
---
次の入力をもとに、`lowlighter/metrics@latest` を利用した GitHub プロフィール構成を日本語で作成してください。

入力:
- GitHubユーザー名: {{Akikukeo1}}
- 表示したい内容: {{表示内容}}
- デザイン方針: {{デザイン方針}}
- 除外したい内容: {{除外内容}}

要件:
- 対象は `{{Akikukeo1}}/{{Akikukeo1}}` リポジトリのプロフィール README。
- GitHub Actions で `lowlighter/metrics@latest` を定期実行する構成を提案する。
- `GITHUB_TOKEN` など必要な Secrets/Permissions を明記する。
- 初心者でも迷わないよう、セットアップ手順を順序立てて説明する。
- セキュリティ上の注意点（最小権限、公開情報の扱い）を含める。

出力形式:
1. 構成方針の要約（3-5行）
2. `README.md` に貼るサンプル（Markdownコードブロック）
3. `.github/workflows/metrics.yml` の完成例（YAMLコードブロック）
4. 導入手順チェックリスト（番号付き）
5. カスタマイズ案（3案、各1-2行）

制約:
- すべて日本語で出力する。
- 例のコードはそのまま貼って動くことを優先し、不要な抽象化をしない。
- 不確実な値は仮定せず、必要なら "要確認" と明記する。
