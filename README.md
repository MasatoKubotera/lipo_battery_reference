<h1 align="center">
  LIPOバッテリーの取り扱い
</h1>

<p align="center">
  Written by <a href="https://github.com/MasatoKubotera">Masato Kubotera</a>
  <br>
  Last updated : <strong>January 21, 2021</strong>
  <br>
  <img src="https://user-images.githubusercontent.com/53966390/105360175-aa01c280-5c3b-11eb-9ef9-04641c5d2daf.jpg" width="480">
</p>

---
<h2>LIPOバッテリーとは</h2>

- リチウムイオンポリマー二次電池
- 寿命・性能はバッテリーの慣らし方・維持方法により変化

---
<h2>特徴</h2>

- エネルギー密度が高い
  - <strong>危険性が高い</strong>
  - 小型・軽量・大容量
- 液漏れしにくい
- メモリー効果がない

  継ぎ足し充電を繰り返した付近で電池電圧が低下する現象

  - 参考：[Panasonic 充電式電池のメモリー効果とは？](https://jpn.faq.panasonic.com/app/answers/detail/a_id/18111/~/%E5%85%85%E9%9B%BB%E5%BC%8F%E9%9B%BB%E6%B1%A0%E3%81%AE%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%BC%E5%8A%B9%E6%9E%9C%E3%81%A8%E3%81%AF%EF%BC%9F%EF%BC%88%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%BC%E7%8F%BE%E8%B1%A1%E3%81%A8%E3%81%AF%EF%BC%9F%EF%BC%89-pz18111)

  <img alt="メモリー効果の例" src="https://jpn.faq.panasonic.com/euf/assets/images/panasonic/answer_images/energy/charge/18422.png" width="320px">

---
<h2>危険性</h2>

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
<h2>GankenKunのバッテリー</h2>

<a href="https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994">HYPERION G5 70Cmax 3S 2600mAh 4.2V-Max LiPo</a>

<img src="https://user-images.githubusercontent.com/53966390/105156368-18b52200-5b4f-11eb-8420-9b269ce50b75.png" width="320px">

- <strong>商品番号</strong> : HP-G570-2600S3

<br>

- [仕様書](https://www.aircraft-japan.com/media/attachment/file/HP-G5SpecSheet.pdf)
- [取扱説明書](https://www.aircraft-japan.com/media/attachment/file/LiPo-Handling-Guide.pdf)

---
<h2>仕様</h2>

- <strong>公称電圧</strong> : 3S・11.1V
- <strong>放電レート</strong> : 最大 70C
- <strong>充電レート</strong> : 最大 6C, 推奨 5C
- <strong>重量</strong> : 220 g
- <strong>寸法</strong> : 116 x 35 x 30mm
- <strong>電源コネクター</strong> : XT-60
- <strong>バランスコネクター</strong> : JST-XH

---
<h2>電圧 V・セル S・容量 mAh</h2>

- <strong>公称電圧</strong>
  端子間の電圧の目安であり，LIPOバッテリーは3.7V/S
  - 最大電圧 : 4.2V/S

- <strong>セル・端子間電圧</strong>
  バッテリーの最小単位であるセルを<u>直列接続</u>することで端子間電圧を上げることができる．
  - 公称電圧 : 3.7V/S × 3S = 11.4V
  - 最大電圧 : 4.2V/S × 3S = 12.6V

- <strong>容量</strong>
  - バッテリーが保持できる電気量
    - 大きいほどより長い時間動作できる．
  - 1時間に流せる電流

---
<h2>バランスコネクタ(バランス端子)</h2>

---
<h2>Cレート</h2>

  １Cとはバッテリーの容量を1時間で<strong>充放電できる電流値</strong>
  
  (例 : 容量 1000mAhの場合の1Cは，1C×1000mA=1000mA=1.0A)

  - 放電レート 最大70Cとは...

    - 容量 2600mAh × 70C = 182,000mA = 182A

  - 充電レート 推奨5Cとは...

    - 容量 2600mAh × 5C = 13,000mA = 13A

---
<h2>充電レート・電圧</h2>

- レート
  <strong><span style="color:red;">必ず推奨充電レートの<u>5C</u>以下</span></strong>で充電を行う．

  (容量 2600mAh × 5C = 13,000mA → 13A以下で充電を行う)

  Brainsで使用している[HiTEC multi charger X4 AC plus](https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994)の<u>最大充電電流は  6.0A </u>．

  最も安全な充電レートは <strong>1C</strong> である．

- 電圧
  適切なバッテリーの電圧で充電を行う．充電電圧を間違えると，<strong><span style="color:red;">発火・爆発</span></strong>する．

  - [【江南市消防本部】リポバッテリー過充電状態により出火！啓発動画](https://youtu.be/IaSGUz0wVsY)

---
<h2>充放電 モード</h2>

[HiTEC multi charger X4 AC plus](https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994)には，4種類の充放電モードがある．

- <strong>バランス充電</strong>
  セル間での電圧差が出ないように調整して充電を行う

  充電する場合は<strong><span style="color:red;">必ずバランス充電モードで充電</span></strong>を行う． 

- <strong>ファスト充電(急速充電)</strong>
  セル間の電圧差を調節せずに，実用可能な容量・電圧まで充電したところで終了させる．

  バッテリーを痛めることはないが，<u>完全な満充電にすることができない</u>．

- <strong>ストレージ充電</strong>
  保管に適切な容量まで充電を行う．
  
- <strong>ディスチャージ(放電)</strong>
  リチウム系バッテリはメモリー効果が無く，放電管理を特に必要としないため使用しない．

---
<h2>過充電・過放電・ストレージ</h2>

---
<h2>寿命・使用中止</h2>

---
<h2>バッテリー 参考資料</h2>

  - [HYPERION G5 70Cmax 3S 2600mAh 4.2V-Max LiPo(英語)](https://hyperion-world.com/en/p2621744-hp-g570-2600s3-13994)

    - [仕様書(英語)](https://hyperion-world.com/media/attachment/file/HP-G5SpecSheet.pdf)

    - [取扱説明書(英語)](https://hyperion-world.com/media/attachment/file/LiPo-Handling-Guide.pdf)

  - [A Guide to Lithium Polymer Batteries(英語)](https://hyperion-world.com/en/blog/view/post/a-guide-to-lithium-polymer-batteries)

---
<h2>充電器 参考資料</h2>

  - [HiTEC multi charger X4 AC plus(日本語)](https://hitecrcd.co.jp/products/x4ac/)

    - [取扱説明書(日本語)](https://hitecrcd.co.jp/material/manual/hitec/HiTEC_X4-ACPLUS_JP_120717.pdf)