# line_and_space_measure

Line and Spaceを測定するための解析プログラムです。

## 概要
このプロジェクトは、画像解析を用いてラインアンドスペースの幅を自動で測定することを目的としています。

## 使用方法
1. `line_and_space_measure.ipynb` をJupyter NotebookまたはGoogle Colabで開きます。
2. 必要なライブラリをインストールします。
3. セルを順に実行してください。

## 画像ファイルの命名規則
入力する画像ファイル名は、以下の形式（Dose_Defocus_Width）にする必要があります。

形式: [Dose]_[Defocus]_[Width].jpg (または .png)

例: 24_-4_5um.jpg


## 注意事項（パスの指定について）
プログラム内で画像フォルダのパスなどを指定する際、Windows環境ではパスの区切り文字が \（バックスラッシュ/円記号）になっている場合があります。 Pythonで正しく処理するために、パス内の \ を / （スラッシュ）に書き換えて実行してください。 （例： C:/Users/Documents/... ）

## 必要なもの
このプログラムは以下の環境・ライブラリで動作します。

### 実行環境
- Python 3.x

### 外部ライブラリ（pip install が必要）
- **NumPy**: 数値計算用
- **Pandas**: データ解析・表計算用
- **Matplotlib**: グラフ描画用
- **OpenCV** (opencv-python): 画像処理用

### 標準ライブラリ（追加インストール不要）
- os, glob, itertools（ファイル操作・ループ処理用）


## セットアップ
このプログラムを実行するには、以下のライブラリのインストールが必要です。
ターミナルやコマンドプロンプトで以下のコマンドを実行してください。

```bash
pip install numpy pandas matplotlib opencv-python





