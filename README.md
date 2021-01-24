<h1 align="center">
  LIPOバッテリーの取り扱い
</h1>

<p align="center">
  Written by <a href="https://github.com/MasatoKubotera">Masato Kubotera</a>
  <br>
  Last updated : <strong>January 24, 2021</strong>
  <br>
  <img src="https://user-images.githubusercontent.com/53966390/105360175-aa01c280-5c3b-11eb-9ef9-04641c5d2daf.jpg" width="480">
</p>

---
<h3>LIPOバッテリーとは</h3>

- リチウムイオンポリマー二次電池
- 寿命・性能はバッテリーの慣らし方・維持方法により変化

---
<h3>特徴</h3>

- エネルギー密度が高い
  - <strong>危険性が高い</strong>
  - 小型・軽量・大容量
- <strong>衝撃・外傷に弱い</strong>
- 液漏れしにくい
- メモリー効果がない

  継ぎ足し充電を繰り返した付近で電池電圧が低下する現象

  - 参考：[Panasonic 充電式電池のメモリー効果とは？](https://jpn.faq.panasonic.com/app/answers/detail/a_id/18111/~/%E5%85%85%E9%9B%BB%E5%BC%8F%E9%9B%BB%E6%B1%A0%E3%81%AE%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%BC%E5%8A%B9%E6%9E%9C%E3%81%A8%E3%81%AF%EF%BC%9F%EF%BC%88%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%BC%E7%8F%BE%E8%B1%A1%E3%81%A8%E3%81%AF%EF%BC%9F%EF%BC%89-pz18111)

  <img alt="メモリー効果の例" src="https://jpn.faq.panasonic.com/euf/assets/images/panasonic/answer_images/energy/charge/18422.png" width="320px">

---
<h3>危険性</h3>

- 取り扱いを間違えると<strong><span style="color:red;">発火・爆発</span></strong>
  - 不適切な充電方法
  - 過放電
  - 過充電

- RoboCupでの事故事例
  - RoboCuup Soccer Small Size League(小型リーグ)
    - [LiPo Battery explosion - RoboCup 2018 SSL](https://youtu.be/aa93h3GrDx8)

  - RoboCup Junior Soccer
    - [【警告】脱・LiPoバッテリーの提唱](http://kamenokokko.blog.fc2.com/blog-entry-58.html)

---
<h3>GankenKunのバッテリー</h3>

<a href="https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994">HYPERION G5 70Cmax 3S 2600mAh 4.2V-Max LiPo</a>

<img src="https://user-images.githubusercontent.com/53966390/105156368-18b52200-5b4f-11eb-8420-9b269ce50b75.png" width="320px">

- <strong>商品番号</strong> : HP-G570-2600S3

<br>

- [仕様書](https://www.aircraft-japan.com/media/attachment/file/HP-G5SpecSheet.pdf)
- [取扱説明書](https://www.aircraft-japan.com/media/attachment/file/LiPo-Handling-Guide.pdf)

---
<h3>仕様</h3>

- <strong>公称電圧</strong> : 3S・11.1V
- <strong>放電レート</strong> : 最大 70C
- <strong>充電レート</strong> : 最大 6C, 推奨 5C
- <strong>重量</strong> : 220 g
- <strong>寸法</strong> : 116 x 35 x 30mm
- <strong>電源コネクター</strong> : XT-60
- <strong>バランスコネクター</strong> : JST-XH

---
<h3>電圧・セル・容量</h3>

- <h4>電圧 V</h4>

  公称電圧とは端子間の電圧の目安であり，LIPOバッテリーは3.7V/S．最大電圧は，4.2V/Sである．

- <h4>セル S</h4>

  バッテリーの最小単位であるセルを<u>直列接続</u>することで端子間電圧を上げることができる．
  - 公称電圧 : 3.7V/S × 3S = 11.4V
  - 最大電圧 : 4.2V/S × 3S = 12.6V

- <h4>容量 mAh</h4>

  - バッテリーが保持できる電気量
    - 大きいほどより長い時間動作できる．
  - 1時間に流せる電流

---
<h3>バランスコネクタ(バランス端子)</h3>

---
<h3>Cレート</h3>

  １Cとはバッテリーの容量を1時間で<strong>充放電できる電流値</strong>
  
  (例 : 容量 1000mAhの場合の1Cは，1C×1000mA=1000mA=1.0A)

  - 放電レート 最大70Cとは...

    - 容量 2600mAh × 70C = 182,000mA = 182A

  - 充電レート 推奨5Cとは...

    - 容量 2600mAh × 5C = 13,000mA = 13A

---
<h3>充電レート・電圧・温度</h3>

- <h4>レート</h4>

  - <strong><span style="color:red;">必ず推奨充電レートの<u>5C</u>以下</span></strong>で充電を行う．

  - Brainsで使用している充電器 : [HiTEC multi charger X4 AC plus](https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994)の<u>最大充電電流は  6.0A </u>．

  - 最も安全な充電レートは <strong>1C</strong> である．

- <h4>電圧</h4>

  適切な電圧で充電を行う．充電電圧を間違えると，<strong><span style="color:red;">発火・爆発</span></strong>する．

  - [【江南市消防本部】リポバッテリー過充電状態により出火！啓発動画](https://youtu.be/IaSGUz0wVsY)

---
<h3>充放電 モード</h3>

[HiTEC multi charger X4 AC plus](https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994)には，4種類の充放電モードがある．

- <h4>バランス充電</h4>

  セル間での電圧差が出ないように調整して充電を行う．充電する場合は<strong><span style="color:red;">必ずバランス充電モードで充電</span></strong>を行う． 

- <h4>ファスト充電(急速充電)</h4>

  セル間の電圧差を調節せずに，実用可能な容量・電圧まで充電したところで終了させる．バッテリーを痛めることはないが，<u>完全な満充電にすることができない</u>．

- <h4>ストレージ充電</h4>

  保管に適切な電圧・容量まで<u>充放電</u>を行う．
  
- <h4>ディスチャージ(放電)</h4>

  メモリー効果がないバッテリーは基本使用しない．

---
<h3>過充電・過放電</h3>

- <h4>過充電</h4>

  - <strong><span style="color:red;">1セルあたり4.2V以上に充電すると危険</span></strong>．

    - 3セルでは，12.6V以上に充電すると危険．

  - 適切な充電電圧で充電を行うことが大切．

- <h4>過放電</h4>

  - 不適切な電圧で長期間放置・限界を超えて放電(使用)を続けた場合になる．
  - <strong><span style="color:red;">1セルあたり3.5V未満に放電すると危険</span></strong>．

    - 3セルでは，10.5V未満に放電すると危険．

  - バッテリーパックが膨らむことがある．
  - 過放電を防ぐために電圧を監視する<u>保護回路</u>が必要．

---
<h3>容量と電圧の関係</h3>

| 容量 % | セル電圧 V/S | 電圧 V/3S | 状態 |
|:---:|:---:|:---:|:---:|
|<span style="color:green;">100</span>|<span style="color:green;">4.20</span>|<span style="color:green;">12.60</span>|<span style="color:green;">満充電</span>|
|<span style="color:orange;">90</span>|<span style="color:orange;">4.11</span>|<span style="color:orange;">12.33</span>|<span style="color:orange;">通常動作範囲</span>|
|<span style="color:orange;">80</span>|<span style="color:orange;">4.02</span>|<span style="color:orange;">12.06</span>|<span style="color:orange;">通常動作範囲</span>|
|<span style="color:orange;">70</span>|<span style="color:orange;">3.95</span>|<span style="color:orange;">11.85</span>|<span style="color:orange;">通常動作範囲</span>|
|<span style="color:orange;">60</span>|<span style="color:orange;">3.87</span>|<span style="color:orange;">11.61</span>|<span style="color:orange;">通常動作範囲</span>|
|<span style="color:blue;">50</span>|<span style="color:blue;">3.80</span>|<span style="color:blue;">11.40</span>|<span style="color:blue;">ストレージ</span>|
|40|3.70|11.1|長期保存|
|<span style="color:red;">20</span>|<span style="color:red;">3.6</span>|<span style="color:red;">10.8</span>|<span style="color:red;">低い電圧</span>|
|<span style="color:red;">10</span>|<span style="color:red;">3.5</span>|<span style="color:red;">10.5</span>|<span style="color:red;">危険</span>|

<strong>60~100%(3S : 11.61~12.60V)の間で使用</strong>．

※上記は典型的なもので，使用状態・年数により異なる場合がある．

参考 : [A Guide to Lithium Polymer Batteries](https://hyperion-world.com/en/blog/view/post/a-guide-to-lithium-polymer-batteries)

---
<h3>保管</h3>

- <h4>電圧</h4>

  - <strong>セル電圧 3.8V/S，端子間電圧11.4V</strong>程度に充放電を行うことで安全に保管できる．
    - 数か月以上の保管 : セル電圧 3.7V/S，端子間電圧11.1V程度にする．

  - <strong><span style="color:red;">満充電したバッテリーを放置することは危険</span></strong>．
    - 24時間以内に使用しない場合はストレージ充電を行う．

- <h4>場所・環境</h4>

  - 常に耐火性の<strong>[セーフティーバッグ](https://hyperion-world.com/en/p1769733-hp-lipo-bag-s)に入れ，燃えにくい場所で保管</strong>．

  - 常温(2~20℃)で保管．冷蔵庫などで保管すると，電池内部に結露が発生し危険．

  - 熱はバッテリーの大敵．熱くなるほどバッテリーの寿命は低下する．

---
<h3>コンディション</h3>

- 

---
<h3>処理・破棄</h3>

1.  バッテリーをできる限り放電させる．
2.  バッテリーからコネクタ部分などを切断し，被膜を剥き放電しやすくする．
    (切断する際にショートしないように細心の注意を払う.)
3.  約5%濃度の食塩水にバッテリーを完全に沈める．
4.  1週間程度，通気性の良い場所に放置し完全に放電させる．
5.  自治体の指示に従い処分する．
    (習志野市では，燃えないゴミとして処分できる．)
<img alt="過放電により膨張したバッテリー" src="https://user-images.githubusercontent.com/53966390/105626642-326aa800-5e74-11eb-8cb3-2a6c1ba66e76.jpg" width="160px">
<img alt="塩水につけた直後" src="https://user-images.githubusercontent.com/53966390/105626584-d6a01f00-5e73-11eb-8a94-ba94482dc4d8.jpg" width="160px">
<img alt="一週間放置後" src="https://user-images.githubusercontent.com/53966390/105626491-4c57bb00-5e73-11eb-86d1-1c25abdabf42.jpg" width="160px">

---
<h3>慣らし</h3>

---
<h3>バッテリー 参考資料</h3>

  - [HYPERION G5 70Cmax 3S 2600mAh 4.2V-Max LiPo(英語)](https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994)

    - [仕様書(英語)](https://hyperion-world.com/media/attachment/file/HP-G5SpecSheet.pdf)

    - [取扱説明書(英語)](https://hyperion-world.com/media/attachment/file/LiPo-Handling-Guide.pdf)

  - [A Guide to Lithium Polymer Batteries(英語)](https://hyperion-world.com/en/blog/view/post/a-guide-to-lithium-polymer-batteries)

  - [取り扱いに要注意！リポバッテリーの特徴と危険性、保管方法について](https://atcl-dsj.com/useful/2979/)

---
<h3>充電器 参考資料</h3>

  - [HiTEC multi charger X4 AC plus(日本語)](https://hitecrcd.co.jp/products/x4ac/)

    - [取扱説明書(日本語)](https://hitecrcd.co.jp/material/manual/hitec/HiTEC_X4-ACPLUS_JP_120717.pdf)