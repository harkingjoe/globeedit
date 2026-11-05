# globeedit

![test](https://github.com/harkingjoe/globeedit/actions/workflows/test.yml/badge.svg)

## インストール

必要なパッケージをインストールします。

```bash
$ sudo apt install git python3 g++ make curl freeglut3-dev libglu1-mesa-dev
```

サブモジュールごとリポジトリを取得し、GlobeEditorをビルドします。

```bash
$ git clone --recurse-submodules https://github.com/harkingjoe/globeedit.git
$ cd globeedit
$ make -C lib/GlobeEditor
```

どのフォルダからでも実行できるように、`PATH`に追加します。

```bash
$ echo "export PATH=\"$PWD:\$PATH\"" >> ~/.bashrc
$ source ~/.bashrc
```

## 使い方

