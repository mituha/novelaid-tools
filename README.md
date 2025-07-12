# novelaid-tools / 小説執筆支援ツール

[![Release Obsidian Plugin](https://github.com/mituha/obsidian-novelaid-tools/actions/workflows/release.yml/badge.svg)](https://github.com/mituha/obsidian-novelaid-tools/actions/workflows/release.yml)

**novelaid-tools**は、Obsidianで小説を執筆するための支援ツールです。  
作者がカクヨムへの投稿作品の執筆のために使用するために開発しています。

## ✨ 主な機能

*   **カクヨム記法のサポート**:
    *   文章にルビ（ふりがな）や傍点を付与できる[カクヨム記法](https://kakuyomu.jp/help/entry/notation)をサポート。表現豊かな記述が可能です。
        *   ルビ: `|漢字《かんじ》` または `漢字《かんじ》`
        *   傍点: `《《傍点》》`
*   **AI執筆支援**:
    *   **AIチャット**: 執筆中の文章をコンテキストとして、AIと対話しながらアイデア出しや推敲ができます。
    *   **AIレビュー**: 個性豊かなAIエージェントが、あなたの作品をランダムにレビュー。思わぬ視点からのフィードバックが得られます。

## 🚀 使い方

1.  **カクヨム記法**:
    *   エディタ上でルビや傍点の記法を入力すると、閲覧モードで自動的に反映されます。
2.  **AI執筆支援**:
    *   サイドバーの「AIチャット」アイコンをクリックすると、専用パネルが開きます。
    *   **チャット**: パネル下部の入力欄に質問や指示を入力して、AIと対話します。
    *   **レビュー**: パネル上部の星（★）アイコンをクリックすると、AIエージェントが現在の文章をレビューします。

## ⚙️ 設定項目

プラグイン設定画面では、以下の項目をカスタマイズできます。

*   **Gemin API Key**: (必須) Gemini AIを利用するためのAPIキー。APIキーは [Google AI Studio](https://aistudio.google.com/apikey) から取得できます。
*   **Use AI**: AI機能の有効/無効を切り替えます。

## 📦 インストール方法

### 手動

1.  このリポジトリの[Releasesページ](https.com/mituha/obsidian-novelaid-tools/releases)から最新版のzipファイルをダウンロードします。
2.  ObsidianのVault（保管庫）にある `.obsidian/plugins/` ディレクトリ内に `obsidian-novelaid-tools` という名前の新しいフォルダを作成します。
3.  ダウンロードしたzipファイルを解凍して、含まれる3つのファイルを、作成した `obsidian-novelaid-tools` フォルダに移動します。
4.  Obsidianを再起動し、`設定` > `コミュニティプラグイン` から「Novelaid Tools」を有効化します。
5.  設定画面でAPIキーを入力すれば完了です。

## 🤝 貢献

バグ報告や機能提案は、このリポジトリの[Issues](https.com/mituha/obsidian-novelaid-tools/issues)までお気軽にどうぞ。

## 📝 ライセンス

[MIT License](LICENSE)