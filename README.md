# Bulma_Custom

- CSS フレームワーク Bulma を、Sass ファイルからカスタム化した練習用コードです。
 
# 必要な環境
 
- 特に無し
- macOS （確認できたもの）

# 参考
- Bulma：https://bulma.io
<br>
CSS フレームワーク

- Bulma のカスタム方法：https://bulma.io/documentation/customize/with-sass-cli/

- Bulma 変数：https://bulma.io/documentation/customize/variables/
<br>
カスタム出来る Bulma の変数

- Sass：https://sass-lang.com/install
<br>
sass をコンパイルして css ファイルを作成する

# 使用方法

・Sass のインストール
<br>
<br>

```
brew install sass/sass/sass
```

<br>
・ダウンロード
<br>
<br>

 ```
$ cd （任意の場所）
$ git clone https://github.com/yoshiswift/Bulma_Custom.git
$ cd Bulma_Custom
```
<br>
<br>
・sample.html をブラウザで開く
<br>

（初期状態はテーブルの境界線少し太くしている）

<br>

<img width="150" alt="スクリーンショット 2020-09-15 17 28 05" src="https://user-images.githubusercontent.com/64339302/93191813-ec902b80-f77f-11ea-9fd2-6fa5b1d877b2.png">

<br>
<br>
<br>

・ここからカスタム化（例）

<br>

./sass/mystyles.scss に下記を追加

参考：https://bulma.io/documentation/elements/table/#variables

<br>

```
$table-background-color: green;
```

<br>

・sass ファイルをコンパイル

<br>

```
sass --watch --no-source-map sass/mystyles.scss:css/mystyles.css
```

<br>

・sample.html をリロード

<br>

<img width="150" alt="スクリーンショット 2020-09-15 18 31 48" src="https://user-images.githubusercontent.com/64339302/93193490-e3a05980-f781-11ea-9220-d73810b511b1.png">

<br>
<br>

・もちろん Table 以外でも出来る