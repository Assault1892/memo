# メモ

[あさると](https://twitter.com/SzlyNe_)のメモ用リポジトリ。  
色々あります。雑に書いたコードなども含まれてる（とおもう）ので見る際にはご注意を（リファクタリングしてくれる方募集！）

## 存在するあれそれ

### [avsファイル](./avs)
AviSynth のあれそれ。フレーム補間やモーションブラーなどなど。

### [ffmpegのsh](./ffmpeg)
ffmpegのシェルスクリプト。中身をvimかなんかで弄ってから実行するのを前提としています。  

### [VRChat](./vrchat)
VRChatのメモ。

### [Python](./python)
Pythonのメモ。

## 重要そうなメモ

- ffmpegは高解像度になればなるほどGPUゴリゴリ使ってくれる。  
  1920x1080ではVideo Encodeを10%を使ってくれない。4Kあるいはそれ以上になるともっと使ってくれる・・・のか？（未検証）

- avsファイルはAviutlに食わせる際コーデックを色々入れないと「could not read...」エラーを吐く。
  「LAVFilters」や「ffdshow」を入れると動いてくれる。
