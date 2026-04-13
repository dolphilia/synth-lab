# synth-lab

> **草稿段階** — このリポジトリはまだ初期段階であり、構成・方針は今後変更される可能性があります。

音の生成手法の研究と、ソフトシンセのプロトタイプ開発を行うラボリポジトリ。最終的には、ノードを自由に配置・接続して音やリズムを作り出せる独自の音楽アプリの開発を目指す。

イメージとして近いのは、Cycling '74 の **MAX** や BITWIG の **The Grid**。

## ディレクトリ構成

```
synth-lab/
├── docs/
│   ├── notes/    調査メモ・検討メモ
│   ├── plans/    計画書
│   └── spec/     仕様書（ドラフト）
├── prototypes/   プロトタイプ（1プロトタイプ = 1サブディレクトリ）
└── research/     研究ノート・スクリプト・データ
    ├── data/     音声データ等
    ├── notebooks/ Jupyter Notebook
    └── scripts/  共通スクリプト
```

## 研究テーマ

- **音の生成** — PSG・FM・PCM音源、アナログシミュレーション、物理モデリング、グラニュラー・シンセシスなど
- **フィルター・エフェクト** — 各種フィルター、リバーブ、ディレイ、歪み系など
- **音の解析** — FFT・スペクトログラム・エンベロープ解析など、生成した音を多角的に解析する

## 技術スタック

| 領域 | 技術 |
|---|---|
| プロトタイプ | Node.js / TypeScript / Vite（必要に応じて React・Next.js を追加） |
| 研究環境 | Python / Jupyter Notebook |

## ドキュメント

- [プロジェクト概要](docs/notes/overview.md)
- [ディレクトリ構成](docs/notes/directory-structure.md)
- [研究テーマ](docs/notes/research-themes.md)
- [技術スタック](docs/notes/tech-stack.md)
