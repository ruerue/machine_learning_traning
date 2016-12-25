# GPU technological conference
---
# 概要
日時：2016-10-05   
会場：ヒルトン東京台場   
主催：nVIDIA

# 基調講演(10:00 - 11:40)
会場人数：７人×12列×8ブロック　で満員(立ち見・サテライト会場あり)   
VIP人数は下記。
- Press : 約50人   
- 文部科学省 : 9人   
- 経済産業省 : 3人   
- 産業総合 : 1人   

## ジャンスンファンCEO公演
### 主なトピックス
- コンピューティングの歴史
	- PCの利用	とインターネットの利用の時代(Windows)
	- モバイルとクラウドによるコンピューティングの時代(iphone、AWS)
	- AIとIoTの時代(GPU)
- Deep learningの歴史
	- パターン認識は人間だが、演算の負荷が高すぎた→cudaをもとに10倍、100倍の演算能力に
	- 2012年、数日間のトレーニングで何十年もかかったプログラムに勝つ。

- Deep Learningの能力
	- 画像認識：人間同等以上
	- 音声認識：人間同等

- GPUコンピューティング
	1. HPC；普通のPCTではかい
	2. ビジュアルコンピューティング
	3. AI（6,7年）企業へと生まれかわってきた。

- GTCの状況
	- 2014年と比べてDNN開発者は２５倍に拡大している（nvidiaの製品を使っている人）。

- DNNの状況
	- コンピューティングの新しい形
	- end to endですべてのデバイスをつなげる必要がある
	- 過成長の状況
	- DNNは非常に複雑になっている。
	- 芸術家の絵画を真似たイメージ処理
	- 1500社以上のスタートアップでも利用している

- DNN利用の顧客
	- chainer；世界有数
	- 楽天：レコメンデーション
	- みずほ：金融予測精度をあげる。大きな飛躍
	- abeja：陳列、顧客分析、
	- AOI：ホームカメラ・ロボットで家庭を管理
- ロボットについて
	- 日本のロボット拠点：toyota iit enroute 宇都宮大　千葉大　東北大など
	- 本はロボット革命の震源地
	- 重い物を支える。

- FANACについて
	- ロボットの最も重要な会社
	- 余地保全、生産量最適化
	- 未来の工場構築がnvidiaのAIプラットフォームを選択した。
	- ひとつの人口知能に生産システムを繋げ、かつロボット自体にも人口知能を搭載している。
	- 生産プログラム不要

### これまでのプログラマも同じ状況（戸惑っている）では？
### 閉じてはだめ
### 設計と比較して製造のちからが重要視されている

## ファナック社長
### トピックス
- 消費者のためのAI
- ロボットと対話をしながらものを作る
- 柔軟性をもった工場
- 全ての製造プロセスのロボットを使っていきたい。
- 将来的には多くのロボットが協力して多くのスキルを得ることができれば
- 「やさしく触る」などプログラムを書くのは難しい。
- どうやってスマートファクトリを現実にするか
	- 工場には非常に多くのロボットがあり、網羅的な制御プログラムを書くことはできない。
	- コラボレーション型のロボットが必要

## 自動走行車について
### トピックス
- 自動車・ロボの中心は日本
- AIトランスポーテーション：1000兆円規模
- 自動運転スキルは非常に難しい。シナリオが多すぎる。

- AIの使い方
	1. 認識する（画像）
	2. 推論する（自分が何処にいるのか、何をすべきなのか）。
	3. ドライビング

- 自動運転AutoCruise（DRIVE PX 2）
	- 障害物があることを認識するのではなく、安全なスペースをリアルタイムで認識しながら運転する。
	- AIの頭脳が何を認識しているのかを表示し、
	- サイドミラーは必要なし。色んな視野から把握できる。
- 家に帰るAutoChauffeur
- 完全なる自動運転FullAutonomy
	- ネットワークに対してハンドリングを自動車が学習する。
	- 一切情報を与えず、勝手に学習する。
	- ハンドル操作で必要なことを勝手に学習する。
	- レーンマーカーがなくてもOK
	- 田舎でもかってに茂みを認識している、
- BAIDU・TOMTOMが自律走行車開発でNVIDISAを選択


# Visialization 医療への貢献
EIzo
- 診断方法の変化
	- データの取扱の簡素化
	- 処理時間の削減
	- 保管の簡素化
- PACSシステムで情報を管理運用している。
- 診断する画像数が増加している。
- ティアリング（更新線）が出ないため、高性能

# 大規模進化計算による音声認識システム開発の自動化
東京工業大学 篠崎たかお 音声認識
- 特徴量抽出　→　音響モデル＋言語モデル   
- 言語モデル：単語の並び方
- 音響モデルにFF-DNNを利用

- 音声分野で教師データはどう与えるのか
	- 音響　RBM →DNN
	- 言語　RNN   
- 最新GPGPUを用いて数日〜数ヶ月
- NNの構造は試行錯誤的   
	- 進化計算による自動チューニング   
	- 共分散行列適応進化戦略(CMA^ES)
- 認識性能・計算性能を評価→パレート最適
- 240時間ツバメ

# 日立の人工知能への取り組み
日立（Iot・クラウドサービス事業部　HPCソリューションセンタ）清水正明
- 満員＋立見多数 （200人くらい？）
- 社会インフラなどの多くの分野で、DNNに置き換わりつつある
- 日立の特徴
	- 既存システムをモニタリング・制御するシステム
	- 人工知能H
- 強化学習でブランコを漕ぐ
	- レゴでブランコをふる装置
	- 1分でブランコを焦げるようになる。
	- 人が思いもあけないような漕ぎかたを思いつく。
 - 利益などに関するデータは少量
-  人間が気づかないような法則を機械学習で見つめる（跳躍学習？）
	- 店員さんがいる場所
	- 物流の置き場を毎日変える
	- コールセンターの人に休み時間に声がけをする。
- 経営判断の学習
	- 経営判断をYES/NOどちらの意見も言ってくれる。
	- 数十秒で結果出る。
	- 新聞データ、経済白書などのデータベースを利用。
- 類似画像検索：20年くらいやっている。
- 耐雑音の音声認識。複数のマイクを使うことでより強く。
- 高次元医療データの分析
- 動線予測（船舶の奇跡データから）
	- AIS航跡データを過去遡って実施。
	- chainerを使っている。
	- 渋滞を避けるための最適化
	- 危険の予測と回避方法の検討

### 結構オープンデータをつかっているという印象。
### 意外に追いつける？
### 柔軟。自社の情報をいかに利用可能な状態で保存していたかが重要になる。
### CADなど、なるべく早く蓄積開始せねば


# MATLABで始めるGPUコンピューティング
MathWorks Japan、太田英司
- MATLABは書くコードが少ない
- parallel computing toolboxの高速化に関して

1. GPUArray
GX = gpuArray(X); GY = fft2(GY);Y = gather(GY);
	フィルターの高速化→さっきの分を加えるだけ
	スペクトル法の高速化（波動方程式）→ gpuArray()で変換

2. 関数のオプションを追加する
	 .....,'useGPU')
 
3. もともと使うようになっている。
	CNNも10行で書ける。

# irayを活用した新しい建築設計
博報堂プロダクツ
- CGの専門家230人が集結している
- Iray for max（Iray+）でレンダリング
- Mterial Definision Language　(材料定義言語)
- vMaterialでマテリアルを選ぶ
- Iray server + VCA

# 時系列センサデータのDeep learningによる異常検知
マクニカクラビスカンパニー（技術商社）
- ディープラーニングは素人
- エッジコンピューティング；問題が顕在化する前に対応
- 組み込みGPUに高い将来性を感じる。
- 故障検知・予知システム
- モータの異常を検知する予知システムを構築した。（専門家のコンサルタントに相談した。）
- DNNモデルの構築はCafeeを使っ構築した・
- ISOの規定から不具合例を洗い出した。→周波数分析が必要。FFTかけてDNNした。
- モータに加速度センサーが取り付けてあった。
- マイコンボードに受け、JetsonTX1におくって処理する。
- 教師データ：自分で手作業で異常を記入する。

### まずこのレベルでやってみてはどうか

# Deep learning for Industry
クロスコンパス・インテリジェンス（2011東工大発ベンチャー、AIの駆け込み寺（日経テクノロジー））
- 60件の実績
- 画像・音声・時系列異常検知・言語処理
- ニーズをしっかり捉える
- NNの構築ノウハウを選んで選ぶ→共有したい
- データ学習
- 学習済みのNNを作るとたくさん活用できる。
- サーバから組み込みまで色んなプラットフォームで動く
- データ多すぎる。→エッジでコンピューティングする必要がある。
- 異常な可能性があれば異常→人間の判断が必要
