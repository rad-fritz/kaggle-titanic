# kaggle-titanic
## 日記
### 2023年8月9日
titanic02作成．
Pytorch本とその他ウェブサイトを参考にしながら(ほぼほぼ真似しながら)，とりあえず訓練の実装をしてみた．
正しく実装できている気がしなかったものの，一応損失のグラフの形的にはそれっぽくなった．

### 2023年8月11-12日
titanic03作成．
ソースコードを整理〜初めてのsubmissionまで！
多値分類を今後実装するときにも使えるように，sigmoid関数での2値分類から，softmax関数で2値に分類するように仕様変更．
<br>
学習したパラメータの読み書き，データの保存など，初めてのことだらけだったものの何とか動かせたよう．
LBスコアはScore: 0.73444でRank 13466．
<br>
Deep Learningより木系の方が相性が良いらしい分野で，特徴量エンジニアリング的なこともしてないので，この結果でもまずまずかというところ．
構造化データより画像がやりたいので，これ以上深めるのはさておき次は初心者向けの過去画像コンペでCNNに挑戦してみたい．
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE5NTM2MjcxNiwtMTk0NTA0NDc5MywtNj
UzOTc1MjAyLC0xNTc2NDg5OTk2LC0xNjkyMTk5MTEzXX0=
-->