# awesomebook_v2

## 『改訂新版 前処理大全』のサンプルコード

本橋智光，橋本秀太郎　著
B5変形判／448ページ
定価3,740円（本体3,400円＋税10%）
ISBN 978-4-297-14138-7
技術評論社、2024年発行

<https://gihyo.jp/book/2024/978-4-297-14138-7>


## 各言語の前処理実行方法

### SQL (BigQuery) の前処理実行

1. BigQueryの利用開始、プロジェクト作成
  - https://cloud.google.com/bigquery/docs/introduction
2. データセット作成、Parquetファイルからの読み込み
  - https://cloud.google.com/bigquery/docs/batch-loading-data
  - 本書のコードではデータセット名はexampleにしていますが、任意の名前で構いません。
  - データセット作成後、dataフォルダ下のParquetファイルをアップロードし、テーブルを作成してください。
3. 各前処理の実行
  - codeフォルダ配下の`*_sql.ipynb`ファイル内の前処理コードを実行します。
  - 実行は次のような方法があります。
    - コンソール（Web）にコードを貼り付けて実行
    - Colabにipynbファイルをアップロードして実行
    - ローカルのJupyterやVSCodeでipynbファイルを実行

### Python (pandas、Polars) の前処理実行

ここではPoetryを用いた簡単な環境構築方法を紹介します。

1. Pythonのインストール
  - https://www.python.org/
2. Poetryのインストール
  - https://python-poetry.org/
3. リポジトリのルートで下記コマンドを実行し、必要なライブラリをインストール
  - `poetry install`
4. JupyterLabを起動
  - `poetry run jupyter lab`
5. 各前処理の実行
  - codeフォルダ配下の`*_pandas.ipynb`ファイルや`*_polars.ipynb`ファイル内の前処理コードを実行します。


## 目次

* Part 1　前処理の基礎知識
  * 第1章　前処理とは
  * 第2章　SQL
  * 第3章　pandas
  * 第4章　Polars
* Part 2　データの構造を対象とした前処理
  * 第5章　抽出
  * 第6章　集約
  * 第7章　結合
  * 第8章　分割
  * 第9章　整形
* Part 3　データの内容を対象とした前処理
  * 第10章　数値
  * 第11章　カテゴリ
  * 第12章　日時
  * 第13章　文字列
  * 第14章　ウィンドウ関数
* Part 4　実践前処理
  * 第15章　演習問題

## サポートページ

https://gihyo.jp/book/2024/978-4-297-14138-7

## ライセンス

TBD