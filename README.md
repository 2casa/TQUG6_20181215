# Tokyo Quantopian Users Group Vol.6

このレポジトリに含まれる資料は、2018/12/15(Sat)に行われた [Tokyo Quantopian User Group Vol.06 ](https://quantopian-tokyo.connpass.com/event/105587/) で使用した発表資料です。

ファイルはjupyter notebook形式です。これを実際に動作させるためには、[Quantopian](https://www.quantopian.com/)のアカウントが必要です。アカウント作成後、自分のResearch環境にnotebookをimportすることで実行可能となります。

当日のタイムテーブルは以下の通り。

## TQUG Vol.6 "Fundamental Factor Model" タイムテーブル

時間は目安です。適宜休憩入れます

## 13:00 Opening.
* 会場スポンサー様よりSmartTrade社及びQuantXサービス説明

## 13:10 Part.0 はじめに

* 自己紹介
* 資料配布、Quantopianセッティングなどの準備時間

## 13:30  Part.1 基礎知識

* 基本的な知識についての説明を行います
  * ファンダメンタル分析ってなに？
  * ファンダメンタル分析と、テクニカル分析
  * アノマリー
  * ファクターモデル
    * 収益（リターン）は何から生じる？
    * リターンモデルとリスクモデル
    * 有名なリスクモデル
      * シングルファクターモデル： -CAPM-
      * マルチファクターモデル： - Fama-French 3factor
      * それ以外（Barraなど、既存の商用モデルについていくつか）

## 14:00  Part.2 Quantopian基礎知識

* QuantopianのNotebookを使って、ファクターモデルの構築に必要な処理を学習する。
  * Quantopianでできること
     * パイプライン
     * スクリーニング（フィルタリング）
  * Quantopianで使える株価以外のデータ（ファンダメンタルデータ）

## 15:00  Part.3 ファクター（アルファ）の探索

* QuantopianのNotebookを使って、予測精度の高いファクター（アルファ）を発見する方法を学習する。
  * Quant Workflow とはなにか？
  * Alphalens を使ったアルファの探索
    * IC(情報係数)とは？
    * zscoreとは？

## 16:00  Part.4 アルゴリズムとして登録してバックテストしよう

* ここまでの内容をベースに、アルゴリズムとして登録してバックテストを行う
  * ポートフォリオ最適化（Objective Function / Constraints）についての解説
  * Quantopian Contest Criteria
  * ハンズオン（ここまでの知識を使って、Quantopian Contest Criteriaをパスするアルゴリズムを作る）

## 17:00  Closing. 質問会

* 勉強会を通じてわからなかったこと、感想等を共有しましょう
