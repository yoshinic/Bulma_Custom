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
```
brew install sass/sass/sass
```

・ダウンロード
 ```
$ cd （任意の場所）
$ git clone https://github.com/yoshiswift/Bulma_Custom.git
$ cd Bulma_Custom
```

・sample.html をブラウザで開く

<img width="150" alt="スクリーンショット 2020-09-15 17 28 05" src="https://user-images.githubusercontent.com/64339302/93191813-ec902b80-f77f-11ea-9fd2-6fa5b1d877b2.png">









・sass ファイルをコンパイル
```
sass --watch --no-source-map sass/mystyles.scss:css/mystyles.css
```



