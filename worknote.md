## 手順
* SU-8055 の tape から音声が出るかチェック
* インターフェース決定
* 筐体設計
* 基板設計

## SU-8055 の tape REC OUT から音声が出るか？
rec selector を aux にすると REC OUT から音声が出る．

## インターフェース
* 電源 (AC IN)
* SIGNAL IN (3.5mm メス)
* SIGNAL OUT (ターミナルブロック)
* ボリューム
* 電源スイッチ
* 電源 LED
* FUSE

電源スイッチ定格は 100VAC 3A．([Q22](https://akizukidenshi.com/catalog/g/gP-00300/) )．
トランスの定格 24V1A  = 24W を考えれば，1次側は 24/100 [A] で余裕あり．

## ゲインとカットオフ周波数を再考
もう一度測定して定数を決め直す
