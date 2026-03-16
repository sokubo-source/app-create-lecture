# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

Claude Code初心者向けのレクチャースライド。reveal.js（CDN読み込み）を使ったシングルページHTMLプレゼンテーション。

## 構成

- `index.html` — スライド本体（reveal.js 5.1.0をCDNから読み込み）

## 開発

ローカルファイルを直接ブラウザで開くだけで動作する（サーバー不要）。

```bash
open index.html
```

## スライドの構造

- `<section>` が横方向のスライド（矢印キー左右）
- ネストした `<section>` が縦方向のサブスライド（矢印キー上下）
- カスタムCSSクラス: `.cmd-box`（コマンド表示）、`.tip-box`（Tips）、`.warn-box`（警告）、`.term-box`（用語解説）、`.feature-grid`+`.feature-card`（機能カード）

## 注意事項

- 対象読者はClaude Code未経験者。専門用語には必ず解説を付ける
- Mac/Windows両対応の記述にする
- 日本語で記述
