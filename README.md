# Pandas 基本講座
LinkedInラーニングの「Pandas 基本講座」コース用のリポジトリです。このコースは [LinkedInラーニング][lil-course-url]で視聴できます。

![Pandas 基本講座][lil-thumbnail-url] 
ビッグデータを高速に処理できるようになった現在、データアナリストやデータサイエンティストの活躍の分野は大きく広がっています。PythonではPandasライブラリを使ってデータ分析を始めます。このコースはPandasの基本を学ぶ講座です。AnacondaをインストールしてJupyterノートブックでプログラムを作成し、Pandasライブラリでできることを学びます。データの抽出や連結、欠損値の処理やグループ化による集計などのPandasライブラリの関数やメソッドの機能の使い方だけでなく、MatplotlibやSeabornライブラリを使ってグラフを作成しデータを可視化して行く方法も説明します。データ分析をより身近に感じてもらえるように架空のスポーツクラブのデータを用意しました。このコースでデータアナリストやデータサイエンティストを目指す第一歩を踏み出しましょう。

## リポジトリの使い方
このリポジトリには必要に応じてブランチが設けられています。ブランチのポップアップメニューを使用して、使用するブランチに切り替えたあとにコースを視聴してください。またURLに`「/tree/ブランチ名」`を追加することで、アクセスしたいブランチに移動することも可能です。

## ブランチ
ブランチはレッスンごとに作成されている場合があります。その場合はブランチ名に`「章番号_レッスン番号」`が付けられています。例えば`「02_03」`という名前のブランチは、2章の上から3番目のレッスン用のブランチとなります。

レッスン前と後のコードを格納しているブランチもあります。該当ブランチには「開始時」（beginning）を表す`「b」`と、「終了時」（ending）を表す`「e」` がブランチ名についています。`「b」`のブランチにはレッスン開始時点のコードが、`「e」`のブランチにはレッスン終了時点のコードが格納されています。また「main」のブランチにはコードの最終形が格納されています。

ファイルに変更を加えた後に、エクササイズファイルのブランチを次のブランチに切り替えたさい、次のようなメッセージが表示されることがあります。

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

この問題を解決するには：
	
    次のコマンドで変更を加えます：git add .
	次のコマンドで変更をコミットします：git commit -m "some message"

## インストール
1. Anacondaをインストールしてください。
	- [Anaconda](https://www.anaconda.com/download)
2. notebookフォルダとdataフォルダを同じフォルダの同じ階層に配置してください。
3. Jupyter Notebookを起動して、notebookを開いてください。

### インストラクター

**金宏 和實**

_株式会社イーザー副社長、テクニカルライター_

この講師の他のコースを視聴する：[LinkedInラーニング](https://www.linkedin.com/learning/instructors/21400000)

[lil-course-url]: https://www.linkedin.com/learning/visual-studio-2022-essential-training
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQGAa1zSEXi2Tw/learning-public-crop_675_1200/0/1691434156196?e=2147483647&v=beta&t=aYWRVBoP5xpkbF9ObzIXCw5JV3zJ0fFajK0MFYx9YYk
