# 生産管理システム (Production Management System)

製造業向けの生産計画・在庫管理システム。Access VBA + Python + HTML/JavaScriptで構築。

## 概要

- **営業計画入力**: Excelテンプレートからの一括取込、履歴管理、変更比較
- **生産計画管理**: 版・改定管理、平準化分析
- **ダッシュボード**: HTMLでリアルタイム可視化（Chart.js）
- **クロス集計表**: 品番×月の計画数、担当者・工場別フィルタ
- **マスタ管理**: 製品・担当者情報の管理

## 技術スタック

- **Backend**: Microsoft Access, VBA
- **分析**: Python (pandas, matplotlib, Plotly)
- **Frontend**: HTML/CSS/JavaScript, Chart.js
- **環境**: Google Colab

## 主な機能

### 営業計画管理
- Excelからの一括取込
- 入力日ごとの履歴管理
- 前回との変更比較（増減を色分け表示）

### 生産計画管理
- 営業計画からの自動変換
- 版・改定管理
- 平準化分析（変動係数CV計算）

### ダッシュボード
- 工場別負荷グラフ
- KPI表示（前版比較）
- インタラクティブなフィルタ

## ドキュメント

- [要件定義書](要件定義書.md)
- [操作マニュアル](操作マニュアル.md)
- [ER図](ER図.png)

## 開発背景

製造業の現場で、Excelベースの管理に限界を感じ、10ヶ月でゼロから構築。
AI（Claude）を活用しながら、業務知識とシステム開発スキルを融合。

### 解決した課題
- データの一元管理
- 履歴管理の自動化
- 工数削減（集計作業: 2時間 → 5秒）
- HTMLでのリアルタイム可視化
- 生産平準化の容易化

## 開発期間

2024年4月〜2025年2月（10ヶ月）

## 期待される効果

- **工数削減**: 集計作業 99.9%削減
- **コスト削減**: 外注開発費 500〜700万円削減
- **品質向上**: 手作業ミスの撲滅
- **意思決定の迅速化**: リアルタイム可視化

## 今後の展開

- SQLサーバーへの移行
- Web API化
- Python/Flaskでの再構築
- クラウド化

## ライセンス

MIT License

## 連絡先

GitHub: [@Tom-zep](https://github.com/Tom-zep)# production-management-system
For manufacturing division 
