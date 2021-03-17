# 僕たちは「PR-card」というサービスを作りました。  
※<b>サービスです！ </b>5分間のデモで実装した機能の全てを紹介することはできません。気になる方は声をかけていただきたいです！！

![ロゴ](https://initial-practice.s3-ap-northeast-1.amazonaws.com/second-sprintReview/logo.png)

---
- 推しアイデア
ただお互いの情報(名刺)を電子的に交換するだけでなく、ARでの閲覧も採用しこれまでに存在しているサービスのとの差別化を図りました。  
自分の名刺を作成する際にテキスト入力だけでなく、音声入力を採用することでこれまでにないUXをお届けします。
 
- 押し技術
Swift/nodejs/Go/Heroku/Docker/AWS/GCP/zip
 
 - サービスの説明(一言ぐらい)
面倒な名刺交換や自己紹介を場所に囚われず、ARで簡単に楽しく！！

## Service function
- 名刺作成機能
- 名刺閲覧機能(AR)
- 所持名刺一覧表示機能
- 所持名刺詳細表示機能
- 名刺更新機能

## Service Architecture
![アーキテクチャ](https://initial-practice.s3-ap-northeast-1.amazonaws.com/second-sprintReview/architecture.png)

## Business model
- 広告モデル  
名刺の一覧を表示する画面で違和感の内容に広告を挟むことで違和感のないプロモーションを行います。
- 課金モデル  
名刺の保存できる枚数に制限をかけ、その上限増加や広告非表示などを提供する代わりに月額料金で課金していただきます。課金形態はサブスクリプション方式を想定しています。  

---
---
## member  
公立はこだて未来大学3年  
- 木村圭太(iOS)
  - 飲んだレッドブル 6本
- 鳥山英峻(iOS)
  - 飲んだレッドブル 6本
- 工藤海斗(iOS)
  - 飲んだレッドブル 6本 
- 西川昂志(backend:node.js * GCP)
  - 飲んだcoffee 12杯
- 若松丈人(backend:go)
  - 飲んだレッドブル 6本
- 大崎敬太(backend:go) 
  - 飲んだレッドブル 4本(初日のみ)
#### 採用開発手法  
飲酒駆動開発

## Why we made it  
僕たちの学校はこの１年間ずっとオンラインで授業を行っており、学校に登校した回数は５回ほどです。  
そのためオンライン上でのグループワーク、ミーティングが当たり前となりました。

さらにこれから<b>就活</b>が始まります。

オンラインでのさまざまな活動を通して感じたニーズは「相手が目の前にいなくても自分の経験や人柄を簡単に紹介できるようなものが欲しい」というものでした。
 
そこで次世代の名刺交換アプリ「PR-card」を開発しました。

このサービスを作ることで自分たちのニーズを満たしつつ、成果物として自分たちの持つ技術のアウトプットもすることができました！！！！

## What we challenged
- AR(座標管理がとても難しかった)
- グラフ描画
- nodejsもexpressもGCPも触ったことなかった（仮想DOMでめちゃボコボコにされた）
- 画像検出(初めて使用するフレームワークの理解に苦労した)
- 音声入力やスライドバーを用いた直感的な操作
- 将来使われることを想定した近未来的デザイン

# Hackathon achievements  
![Fate](https://initial-practice.s3-ap-northeast-1.amazonaws.com/second-sprintReview/bug-min.png)


# Unimplemented Service Architecture
![Unimplemented Service Architecture](https://i.gyazo.com/6c19c2e5bc8cc02d59fca4a7efc070f3.png)
