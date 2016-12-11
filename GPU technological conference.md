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

## 主なトピックス
- コンピューティングの歴史
	- PCの利用	とインターネットの利用の時代(Windows)
	- モバイルとクラウドによるコンピューティングの時代(iphone、AWS)
	- AIとIoTの時代(GPU)
- Deep learningの歴史
	- パターン認識は人間だが、演算の負荷が高すぎた
 
### PCインターネット　モバイルークラウド　AIーAOT
GPU-Deep learningにより始まった

パターン認識がこの人間と知能の基本
演算不可が高すぎる →　cudaをもとに10倍、100倍に
2012年、アレックスネットを開発　対象物を認識した。→数日間のトレーニングで何十年もかけたものにかった。
膨大な脳が必要。
2012年、大規模なブレインが開発された。


GPUが費用なのは》認識している、ISPはDNNを採用した。
画像認識：人間同等以上
音声認識：人間同等
→舞台は整った。

GPUコンピューティング
１．HPC；普通のPCTではかい
２．ビジュアルコンピューティング
３．AI（6,7年）企業へと生まれかわってきた。

「もはやSFではない。」

アイアンマンの研究所でのはなし
ﾄﾆスタークと一緒に作る。

GTC：
2014年と比べてDNN開発者は２５倍に拡大している。
（nvidiaの製品を使っている人）

なぜAIにGPU？
脳はGPU（メンタルイメージ）
絵を思い浮かべる。
小さなプロセッサが計算している。


step1: 学習する。
新しいコンピューティング
アーキテクチャを作成（モデル作成）→推論→デバイス→学習→
### これまでのプログラマも同じ状況（戸惑っている）では？
か成長の状況ではないか。完全なるプラットフォームを作る。
すべてのデバイスをつなげる必要がある。end to end

DNNは非常に複雑になっている。
演算能力は成長するが、過成長なモデル
パスカル：DNNに最適化されたGPU
20奥ドル、４年で６４倍

step2 本番環境にデプロイする。
TEsLA P4:データセンターでの推論処理
推論処理（データセンター用）
### 閉じてはだめ
tensorRT
NNについて、パターン認識以外には？
独自の芸術作品に適用することができる
ピカソスタイル。
リアルタイム！
ありとあらゆるイメージ処理ができる

あぷり、クラウド、PCｗｐ
クラウドから使うことができる。
1500者以上のスタートアップでもつかっている。


chainer；世界有数
楽天：レコメンデーション
みずほ：金融予測精度をあげる。大きなひやく
abeja：陳列、顧客分析、

AOI
ホームカメラでの認識妻が帰ってきた。
裏庭にはだれもこない。
マイクをつなげると、ロボットができる。

JETSON TX1海込みAIす＾パ＾コンピュ＾た
ソフトウェアを載せることもできる

日本はロボット革命の震源地
重い物を支える。
toyota iit enroute 宇都宮》だい　千葉大　東北大など

もっとも重要な会社がFANAC
未来の工場構築がnvidia AI  プラットフォームを選択。
プラグラムを書かなくてもよい。
ひとつの人工知能につな得る。
画像

ロボット字体もAIを搭載。
FANACビデオ紹介。
物を運んでいる。

予知保全

## ファナック
消費者を考えて
将来、どういった製品が人気になるかわからない。
ロボットと話しながらつくる。
### 設計と比較して製造のちからが重要視されている
将来的には多くのロボットが協力して多くのスキルを得ることができれば
「やさしく触る」などプログラムを書くのは難しい。
すべての製造プロセスをロボットを使っていきいた
・コネ口火ティ
・オールマイティ（多機能）
・AI
どうやってスマートファクトリを現実にするか
工場内で実行したい。
違い；応答時間が早いことが必要。（複数台のロボットが高速に認識して実行する）
非常に多くの農民素がある。
→ソフトウェアのプログラムが書けない。→
コラボレーション型のロボットが必要
工場が確信され得るだけでなく、他業界（重工業など）に対して
自動車が５０％。他のセグメントは小さい→多くの可能性がある。

##  もどり
### 自動走行車について
自動車・ロボの中心は日本
AIトランスポーテーション：1000兆円規模
自動運転スキルは非常に難しい。シナリオが多すぎる。

AIの使い方
１．認識する（画像）
２．推論する（自分が何処にいるのか、何をすべきなのか）。
３．ドライビング

DRIVE PX 2
自動運転AutoCruise
家に帰れAutoChauffeur
完全なる自動運転FullAutonomy

障害物があることを認識するのではなく、
安全なスペースをリアルタイムで認識しながら運転する。

AIの頭脳が何を認識しているのかを表示し、
サイドミラーは必要なし。
色んな視野から把握できる。

ネットワークに対してハンドリングを自動車が学習する。
一切情報をあたえない。
BB８は勝手に学習する。
レーンマーカーがなくてもOK
BB8のみているもの
ハンドル操作で必要なことをかッテに干出する。
田舎でもかってに茂みを認識している、

BAIDU TOMTOM　が自律走行車開発でNVIDISAを選択

XAVIER 
AIすーおあーコンピュータSOC


## Visialization 医療への貢献
EIzo
### 診断方法の変化
- データの取扱の簡素化
- 処理時間の削減
- 保管の簡素化

PACSシステムで情報を管理運用している。

### 続纓（診断する画像数）が増加している。
画像（情報）が増えている。

ティアリング（更新線）がでてしまうので高性能

## 大規模進化計算による音声認識システム開発の自動化
東京工業大学
篠崎たかお
音声認識

特徴量抽出　→　音響モデル＋言語モデル   
言語モデル：単語の並び方

音響モデルFF-DNN

### 音声分野で教師データはどう与えるのか
音響　RBM →DNN →　   
言語　RNN   
最新GPGPUを用いて数日〜数ヶ月

NNの構造をどのようにすればいいのかは試行錯誤的   
→進化計算による自動チューニング   
→共分散行列適応進化戦略(CMA^ES)

認識性能・計算性能を評価→パレート最適

学習データ240時間ツバメ

## 日立の人工知能への取り組み
日立
清水正明
Iot・クラウドサービス事業部　HPCソリューションセンタ

満員＋立見多数 （200人くらい？）

社会インフラなどの多くの分野で、DNNに置き換わりつつある
### 人多い
日立の特徴
既存システムをモニタリング・制御するシステム
人工知能H

レゴでブランコをふる装置
1分でブランコを焦げる
人より漕げることを思いつく。

利益などに関するデータは少量のため、
跳躍学習
店員さんがいる場所
物流の置き場を毎日変える
コールセンターの人に休み時間に声がけをする。
→気づかない！
### 柔軟な文化

経営判断をYES/NOどちらの意見も言ってくれる。
数十秒で結果出る。
新聞データ、経済白書などのデータベースを利用。

### 柔軟。自社の情報をいかに利用可能な状態で保存していたかが重要になる。
### CADなど、なるべく早く蓄積開始せねば

類似画像検索を20年くらいやっている。

鯛雑音の音声認識。複数のマイクを使うことでより強く。

高次元医療データの分析

動線予測（船舶の奇跡データから）
AIS航跡データを過去遡って実施。

### 結構オープンデータをつかっているという印象。
船舶chainerを使って予測。
### 意外に追いつける？
渋滞を避けるための最適化
危険の予測と回避方法の検討

計算機について
DGX-1
Testla


## MATLABで始めるGPUコンピューティング
MathWorks Japan
太田英司

MATLAB書くコードが少ない
parallel computing toolbox

toolboxの高速化に関して


１．GPUArray

GX = gpuArray(X);
GY = fft2(GY);
Y = gather(GY);

フィルターの高速化
→さっきの分を加えるだけ

スペクトル法の高速化（波動方程式）
→gpuArray()で変換

２．関数のオプションを追加する
 .....,'useGPU')
 
３．もともと使うようになっている。
CNNとか

CNNも10行で書ける。

## irayを活用した新しい建築設計
博報堂プロダクツ

CGの専門家230人が集結している
レンダリング等の道具の整理

Iray for max（Iray+）でレンダリング
Mterial Definision Language　材料定義言語
vMaterialでマテリアルを選ぶ
Iray server + VCA

## 時系列センサデータのDeep learningによる異常検知
マクニカクラビスカンパニー（技術商社）
ディープラーニングは素人

ロボッと、工作機械、モーターなど時系列データDNNで異常検知
jetson tx1 教師あり

エッジコンピューティング；問題が顕在化する前に対応
組み込みGPUに高い将来性を感じる。
故障検知・余地システム

モータの異常を検知する予知システムを構築した。
（専門家のコンサルタントに相談した。）

DNNモデルの構築はCafeeを使っ構築した・
CAVIS　ABeamConsulting

データの取得と加工、デモづくり
ISOの規定から不具合例を洗い出した。
→周波数分析が必要。FFTかけてDNNした。
モータに加速度センサーが取り付けてあった。
STFFT：512ptのFFTかけている。
マイコンボードに受け、JetsonTX1におくって処理する。
教師データ：自分で手作業で異常を記入する。

### まずこのレベルでやってみてはどうか

## Deep learning for Industry
クロスコンパス・インテリジェンス
2011東工大発ベンチャー
AIの駆け込み寺（日経テクノロジー）

60件の実績

画像・音声・時系列異常検知・言語処理

1. ニーズをしっかり捉える
- NNの構築ノウハウを選んで選ぶ→共有したい
- データ学習
- 学習済みのNNを作るとたくさん活用できる。
- サーバから組み込みまで色んなプラットフォームで動く

学習データを共有したい:IX

データ多すぎる。
→エッジでコンピューティングする必要がある。

ほとんどボタンを押すだけ！をめざす。

異常な可能性があれば異常→人間の判断が必要

LSTM：マイコンで判断


わかった。文末でははあ





