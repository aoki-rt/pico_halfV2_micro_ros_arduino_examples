# pico_halfV2_micro_ros_arduino_examples
Pi:Co Half V2用のmicro-ROS Arduinoサンプルスケッチ集


## サンプルスケッチについて

### STEP1 ~ STEP8

- micro-ROSを使用しないサンプルスケッチです
- Pi:Co Half V2のハードウェアを動かすための、Arduinoスケッチの書き方をまとめています

### STEP9 ~ STEP12

- micro-ROSを使用するサンプルスケッチです
- PCとPi:Co Half V2間で通信するための、Arduinoスケッチの書き方をまとめています

## 関連ソフトウェア

- [pico_msgs](https://github.com/rt-net/pico_msgs) : PCとPi:Co Half V2間でやりとりするROSメッセージを定義したパッケージです
- [pico_ros](https://github.com/rt-net/pico_half_ros) : Pi:Co half V2を便利に動かすためのPC向けROSパッケージ集です

## スケッチファイルの自動整形について

ソースコードのレイアウトを整えるため、各スケッチファイルにはArduino IDEの自動整形を適用しています。
自動整形のルールは[.clang-format](.clang-format) ファイルを参照してください。

## License

(C) 2023 RT Corporation

各ファイルはライセンスがファイル中に明記されている場合、そのライセンスに従います。特に明記されていない場合は、Apache License, Version 2.0に基づき公開されています。  
ライセンスの全文は[LICENSE](./LICENSE)または[https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)から確認できます。

※このソフトウェアは基本的にオープンソースソフトウェアとして「AS IS」（現状有姿のまま）で提供しています。本ソフトウェアに関する無償サポートはありません。  
バグの修正や誤字脱字の修正に関するリクエストは常に受け付けていますが、それ以外の機能追加等のリクエストについては社内のガイドラインを優先します。

