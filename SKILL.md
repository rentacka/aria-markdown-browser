---
name: aria-markdown-browser
description: Aria Markdown Browser (Zero-Script / Zero-Exploit 完全安全 ＆ 0.02秒超爆速 ＆ 広告完全消滅の Markdown 専用 Web ブラウジング・スクレイピング知能スキル)
---

# Aria Markdown Browser (SKILL.md)

Webページ（HTML）からJavaScriptやトラッカー、広告を物理的に完全除去し、0.02秒〜0.5秒の超爆速で美しい構造化Markdown（GFM）として瞬時に閲覧・抽出・保存する軽量ブラウジング知能スキル。

---

## トリガー条件 (Triggers)
- Webページの安全かつ広告なしでの閲覧・Markdown取得を求められたとき
- 大規模言語モデルやエージェントのコンテキスト節約（トークン1/10〜1/50圧縮）のためにWebページを構造化テキスト化したいとき
- 呼び出しキーワード例:
  - 「このURLをMarkdownで取得して」「広告なしでWebページを読みたい」
  - 「安全にスクレイピングして」「ターミナルでWebを閲覧したい」
  - `/aria-markdown-browser`, `fetch-markdown`, `scrape-url`

---

## 前提条件・依存関係 (Prerequisites)
- **実行環境**: Python 3.10+
- **必要パッケージ**:
  ```bash
  pip install requests beautifulsoup4 markdownify

