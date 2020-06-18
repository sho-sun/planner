# README

## アプリ名  
Planner

## 概要  
学習予定を立てると自動で復習計画が入力される。

## 本番環境(デプロイ先　テストアカウント＆ID)  
https://planner-su.herokuapp.com/

## 制作背景   
解決したい課題  
⇒復習計画を立てる際に手間が掛かる点について  
- 予定表を使って学習計画を立てる際に、復習の計画を立てようとすると、以前の学習内容を予定帳で確認して、今日の復習として予定に組み込む作業が発生する。  
- また、エビングハウスの忘却曲線に沿って復習計画を立てようとすると、複数日の復習を１日の計画に盛り込む必要が出てくる。  
- 学習計画を立てる段階でこのような作業を減らし、より学習にコミットできる環境を整える目的でこのアプリを制作しました。  

## アプリ制作で意識したこと3点  

- 需要を考慮した作品になっているか  
コロナウイルスの影響によるリモートワークの普及と、それに伴う作業量の可視化で実力主義社会が到来。  
それによりスキルアップのための学習が増加⇒学習系アプリの需要拡大が予測される。  

- ユーザーを意識した構造か  
UIはシンプル、わかりやすさを重視  
類似アプリの改善案を考案(調査で発見した類似アプリを使用した結果、予定帳と予定記入ページが別で画面遷移に使いにくさを感じたため、予定帳に直接記入する方式を取り入れたい(未実装))  

- 作品に明確な意図が込められているか  
自己の学習の中で感じた課題⇒復習予定を立てるのが面倒で後回しにしてしまい、結局復習しないことが多かった。  
復習してもらうことを目的に設計⇒効率的に復習しようとすると発生する手間を省き、よりよい成果を出したいと思ったことが制作のきっかけ  

## DEMO
1
![image](https://user-images.githubusercontent.com/61076624/83946819-1b783680-a84e-11ea-8c30-4339039b421c.png)
2
![image](https://user-images.githubusercontent.com/61076624/83946856-64c88600-a84e-11ea-8f14-c28bec098746.png)
3
![image](https://user-images.githubusercontent.com/61076624/83946866-701bb180-a84e-11ea-94d5-bb25dfbdf51b.png)
4
![image](https://user-images.githubusercontent.com/61076624/83946875-79a51980-a84e-11ea-89bd-2249146dc6e1.png)
5
![image](https://user-images.githubusercontent.com/61076624/83946881-7dd13700-a84e-11ea-9f99-7ecdc92d13a8.png)

## 工夫したポイント  
予定を立てるだけで復習計画も立てられる点

## 使用技術(開発環境)  
ruby  
ruby on rails  
javaScript  
jQuery

## 課題や今後実装したい機能  
復習予定機能(基本機能)  
予定帳に直接記入する方式  

## DB設計

|Column|Type|Options|
|----|----|-------|
|title|string|-------|
|description|text|-------|
|start_date|datetime|-------|
|end_date|datetime|-------|
|created_at|datetime|null: false|
|updated_at|datetime|null: false|
