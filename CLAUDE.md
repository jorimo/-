# Project: -

## Overview
<!-- プロジェクトの概要をここに記載してください -->
このリポジトリはプロジェクト自動化のテンプレートです。

## Tech Stack
<!-- 使用する技術が決まったら更新してください -->
- 未定

## Development Commands
<!-- プロジェクトに合わせて更新してください -->
```
# ビルド
# npm run build / make build / etc.

# テスト
# npm test / pytest / etc.

# リント
# npm run lint / ruff check . / etc.

# フォーマット
# npm run format / black . / etc.
```

## Coding Conventions
- 日本語コメント可。ただしコード（変数名・関数名）は英語
- 不要なコメントやdocstringは追加しない
- シンプルさを優先。過度な抽象化を避ける

## Git Workflow
- ブランチ命名: `feature/*`, `fix/*`, `docs/*`
- コミットメッセージ: 日本語OK。変更内容を簡潔に書く
- シークレット（.env, credentials）は絶対にコミットしない

## File Structure
<!-- ディレクトリ構成が決まったら記載 -->
```
/
├── README.md
└── CLAUDE.md
```

## Important Notes
- 本番環境に影響するコマンド（デプロイ等）は必ず確認してから実行
- 大きなリファクタリングは事前に方針を相談すること
- テストがある場合、変更後は必ずテストを実行する
