# ADSU01TB USB録音 音源再生モジュール評価ボードセット

## 音源再生モジュールで手軽に効果音再生！スピーカと電源をつなぐだけでそのまま音楽再生機として使用出来ます。

![](https://bit-trade-one.co.jp/wp/wp-content/uploads/2015/09/e978d633edb931e6f49fd2e6ede7eebe.png)  

組み込み機器へ本製品を搭載することで、簡単に目的の音を出力することが可能です。  
また音質についても40kHz以上のサンプリング周波数を持ち、音声だけでなく音楽や効果音の再生も可能です。  
従来の音源モジュールのアナログ音質に満足できなかったユーザーにも安心しておすすめできる音質を持っています。  
またマイコンやArduino／RaspberryPi等の出力ピンからも制御可能でスイッチ入力による  
再生停止により制御可能で組み込み初心者にも安心の音源再生モジュールです。  

## 製品詳細は[こちら](https://bit-trade-one.co.jp/product/module/adsu01tb/)!

### 音源再生モジュール単体のサポートサイトは[こちら](https://github.com/bit-trade-one/ADSU01_Sound_Player_Module)!

## [PCアプリ](https://github.com/bit-trade-one/ADSU01TB_Sound_Player_Module_reference_board/tree/master/App)

## [マニュアル](https://github.com/bit-trade-one/ADSU01TB_Sound_Player_Module_reference_board/blob/master/Manual/ADSU01TB_MANUAL_WEB.pdf)

### [基板図](https://github.com/bit-trade-one/ADSU01TB_Sound_Player_Module_reference_board/blob/master/Dimensions/ADSU01TB%20%E9%9F%B3%E6%BA%90%E5%86%8D%E7%94%9F%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB%E8%A9%95%E4%BE%A1%E3%83%9C%E3%83%BC%E3%83%89%20%E5%A4%96%E5%BD%A2%E5%9B%B3.pdf)

### [回路図](https://github.com/bit-trade-one/ADSU01TB_Sound_Player_Module_reference_board/blob/master/Schematics/pwm_module_demo_schematics.pdf)

## 製品仕様

### 音声出力仕様

 - サンプリング周波数：約40kHz
 - 量子化ビット：8bit　　
 - モノラル　
 - アンプは内蔵されていません

### 音声保存仕様

 - 音声4点合計90秒まで
 
### 入出力仕様

 - スイッチ入力端子　５点　・曲１再生・曲２再生・曲３再生・曲４再生・停止  
 - ステータス出力　１点　・再生ステータス（再生中Hi、停止中Low）  

### ピン配置

 
ピン番号|信号名|説明|I/O
:-|:-|:-|:-
1|+5V|5V入力、USBから電源供給しない場合に使います|
2|GND|GND|
3|GND|GND|
4|STATUS|再生状態を表示します（再生中はH）|O
5|STOP|停止（Lアクティブ）|I
6|PLAY4|4曲目再生（Lアクティブ）|I
7|PLAY3|3曲目再生（Lアクティブ）|I
8|PLAY2|2曲目再生（Lアクティブ）|I
9|PLAY1|1曲目再生（Lアクティブ）|I
10|GND|GND|
11|GND|GND|
12|AOUT|音声出力|O
13|PGC|NC（マイコン書込用）|IO
14|PGD|NC（マイコン書込用）|IO
15|GND|GND|
16|VCC|NC（マイコン書込用）|
17|MCLR|NC（マイコン書込用）|I
18|USB5V|USBから供給された5V|
19|D-|USB(D-)|IO
20|D+|USB(D+)|IO

＊ピン間2.54mm、ピン幅600mil

製品仕様（USB音源 音源再生モジュール評価ボード）

【対応OS】日本語版OS: Windows10, Windows8, Windows7，Vista™搭載のDOS/Vパソコン  
【対応機種】USBポートを標準で持ち、パソコン本体メーカーが上記対応OS上でのUSBポートの動作を保証している機種。  
*(一部対応しない機種があります）NEC PC-9800、PC-9821シリーズには対応しておりません。*  
*設定アプリケーションソフトウェア導入のため別途インターネット環境が必要です。*  
【対応インターフェース規格】USB2.0(タイプminiBコネクタ) USBフルスピードモード  
【対応音源フォーマット】MP3 / WAV / AIFF / OGG / FLAC  
【音源再生仕様】サンプリング周波数：約40kHz　／　量子化ビット：8bit  
【本体寸法】W75.0×D72.0×H19.0mm  
【重量】　約45g  
【動作環境:温度】　0～45℃、湿度10～60％(結露なきこと）  
【生産国】Made in Japan  
【保証期間】お買い上げから6ヶ月間  
