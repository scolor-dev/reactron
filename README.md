# Reactron
# 概要 📝
`reactron` は、 React と Electron を組み合わせたデスクトップアプリ開発用のテンプレートです。
- フロントエンドに React + TypeScript（または JavaScript）
- Electron によるクロスプラットフォーム（Windows / macOS / Linux）対応
- 最小構成で、すぐに開発／ビルドを開始できる構造
このテンプレートを使うことで、ゼロから boilerplate を書かずに、すばやくアプリ開発を開始できます。

# 主な機能／構成
- React + Electron によるベース構成
- renderer/ — React (UI) 側
- electron/ — Electron (メイン／バックグラウンド) 側
- npm スクリプトによる簡易操作: インストール・開発モード・ビルド

# 動作環境／前提条件
- Node.js (推奨バージョン: LTS を推奨)
- npm または yarn
- 開発マシン (Windows / macOS / Linux)

# インストールと初回セットアップ
```
# リポジトリをクローン（またはテンプレートから生成）  
git clone https://github.com/scolor-dev/reactron.git  
cd reactron

# 依存モジュールをインストール  
npm install  

# 開発モードで起動  
npm run dev  
```

# 開発用コマンド
| コマンド | 内容 |
|----------|------|
| `npm run dev` | 開発モードで起動 |
| `npm run build` | アプリのビルド → 配布可能な形式 (exe / dmg など) を出力 |



