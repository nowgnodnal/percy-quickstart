# Percy Quickstart

<!-- シールド一覧 -->
<!-- 該当するプロジェクトの中から任意のものを選ぶ-->
<p style="display: inline">
  <!-- フロントエンドのフレームワーク一覧 -->
  <img src="https://img.shields.io/badge/-Node.js-000000.svg?logo=node.js&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Percy-black.svg?logo=percy&style=for-the-badge">
</p>

## 概要

Percy というビジュアルテストのツールを用いて、２つの画像の差分を検出するためのプロジェクトです。

## 開発環境構築

<!-- コンテナの作成方法、パッケージのインストール方法など、開発環境構築に必要な情報を記載 -->

### 技術スタック

| 言語・パッケージ      | バージョン       | 
| ------------------ | --------------- | 
| Node               | 20.16.0         |
| @percy/cli         | 1.30.2          |


### 環境変数の一覧

| 変数名                  | 役割                                   | 
| ---------------------- | -------------------------------------- | 
| PERCY_TOKEN            | Percy のプロジェクトごとに発行されるトークン |
| PERCY_BRANCH           | Percy のブランチ名                       |

## 動作確認

1. .env ファイルを作成して、環境変数を作成。
2. `index.html` に `v1` の画像をセットし、`npx run snapshot` コマンドを実行。
3. `index.html` に `v2` の画像をセットし、`npx run snapshot` コマンドを実行。

