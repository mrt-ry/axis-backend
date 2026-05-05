# CLAUDE.md（axis-backend）

## プロジェクト概要
axis アプリのバックエンド API サーバー。NestJS 11 + TypeScript で構築する REST API。

## 技術スタック
- framework: nestjs 11
- language: TypeScript 5.7
- test: jest
- api_style: rest

## 開発コマンド
- npm run start:dev : 開発サーバー起動（port 3000）
- npm run build : ビルド
- npm run test : ユニットテスト
- npm run test:e2e : E2E テスト
- npm run lint : lint + 自動修正

## プロジェクト構成
- src/ : ソースコード
- test/ : E2E テスト

## 技術制約
<!-- 実装で非推奨を踏んだら都度ここに追記する -->
