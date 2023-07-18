# ゲーム のタイトル
* コインゲッター

## 実行環境の必要条件
* python >= 3.10.9
* pygame >= 2.1.2

## ゲームの概要
* 上から落ちてくるコインを集めてスコアを稼ぐ

## ゲームの実装
### 共通基本機能
* playerとplayerの移動
* 普通のコイン（スコア、落下速度など）
* スコア

### 担当追加機能
* 背景画像を入れる　（竹下）
* super_coin(魯珺生担当)：集めたら普通のコインの2倍のスコアをもらえる。普通のコインより集めしにくい。
* 防壁(魯珺生担当)：tabを押すとplayerの上に防壁が現れる。コインは防壁にぶつかると消える。
 
* Time機能（担当：マナト）：時間の管理を行うクラスの追加、Timeが0になったら強制終了する機能
* playerの画像追加（山田）
* 爆弾追加（王）
### ToDo

### メモ
* 防壁は追加機能「爆弾」に合わせるために作った機能です。
* コインの機能

