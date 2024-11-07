# 🤗Hugging Face ハンズオン

[![CI](https://github.com/tpu-dsg/hf-hands-on/actions/workflows/ci.yaml/badge.svg)](https://github.com/tpu-dsg/hf-hands-on/actions/workflows/ci.yaml)
[![License](https://img.shields.io/github/license/tpu-dsg/hf-hands-on)](./LICENSE)

Hugging Faceのエコシステムを活用した、モデルやデータセットの使い方を体験します。

## 実行方法

### Google Colab

以下の「Open in Colab」ボタンをクリックしてください。

| コンテンツ | Colab |
| :---: | :---: |
| プレイグラウンド | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tpu-dsg/hf-hands-on/blob/main/src/playground.ipynb) |
| ファインチューニング | [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tpu-dsg/hf-hands-on/blob/main/src/fine-tuning.ipynb) |

### Docker(DevContainer)

NVIDIA GPUマシンでDevContainerが利用可能です。

### その他

[uv](https://github.com/astral-sh/uv)を使って依存関係をインストールできます。

```bash
uv sync
```

## 貢献方法

[リポジトリへの貢献ガイド](https://github.com/tpu-dsg/.github/blob/main/CONTRIBUTING.md)を参照してください。

コミット前には、以下のコマンドでNotebookの不要なメタデータの削除とコードスタイルのフォーマットを行ってください。

```bash
uv run nbdev_clean
uv run ruff format .
```