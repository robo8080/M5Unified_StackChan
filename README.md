# M5Unified_StackChan
独り言を言うｽﾀｯｸﾁｬﾝです。セリフをSDカードにwavファイルで入れておくとランダムに再生します。
<br><br>
@mongonta555 さんの[ｽﾀｯｸﾁｬﾝ M5GoBottom版組み立てキット](https://raspberrypi.mongonta.com/about-products-stackchan-m5gobottom-version/ "Title")に対応しています。<br>

Avatar表示は、meganetaaanさんのm5stack-avatarをベースにさせていただきました。<br>
オリジナルはこちら。<br>
An M5Stack library for rendering avatar faces <https://github.com/meganetaaan/m5stack-avator><br>

---

### M5GoBottom版ｽﾀｯｸﾁｬﾝ本体を作るのに必要な物、及び作り方 ###
こちらを参照してください。<br>
* [ｽﾀｯｸﾁｬﾝ M5GoBottom版組み立てキット](https://raspberrypi.mongonta.com/about-products-stackchan-m5gobottom-version/ "Title")<br>

---

### 必要な物 ###
* [M5Stack](http://www.m5stack.com/ "Title") (M5Stack Core2で動作確認しました。)<br>
* VSCode<br>
* PlatformIO<br>

使用しているライブラリ等は"platformio.ini"を参照してください。<br>

---

### サーボモーターを使用するGPIO番号の設定 ###
* M5Unified_StackChan.inoの13行目付近、サーボモーターを使用するGPIO番号を設定してください。<br>

---

### 使い方 ###
* SDカードに、wavというディレクトリを作りそこにwavファイルを入れておきます<br>
* wavファイルのサンプリング周波数は16khzか24khzにしてください。<br>
* ファイル名に全角文字や長いファイル名はつかえません。<br>
* サンプルのwavファイルがwavディレクトリに入っています。<br>
この音声データは[「VOICEVOX;ずんだもん」](https://voicevox.hiroshiba.jp/ "Title")を使用して作成しました。<br>
<br><br>
