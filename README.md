# 課題 14-2: ファイル読み込み

### 課題の説明
テキストファイル「textfile1.txt」の読み込みとその内容の画面へのprintを行うProgE2.mainメソッドの作成と実行をしなさい。

- ファイル名はString型変数を定義して実行時引数として与えること
- ファイル読み込みで用いるFileReaderのコンストラクタやread()、close()はIOExceptionを送出する可能性があるので、例外をキャッチして対処できるようにしておくこと

ヒント: try-with-resources文を使った例外処理(教科書17.5.4 ~17.5.6)を行うと簡潔に書ける

(注)　BlueJで動作の確認をするには、「textfile1.txt」をプロジェクト unitE2 のフォルダにコピーしてください。
### textfile1.txt
```
1.読み込み確認用ファイル
2.ここは2行目です。
3.
```

### 実行結果（実行時引数を　textfile1.txt　とした場合）
```
1.読み込み確認用ファイル
2.ここは2行目です。
3.
```