# tier4_autoware_msgs with External Planner

本リポジトリは、[Autoware.universe](https://github.com/Toyota/autoware_universe)において、外部のカスタムプランナー(`External Planner`)への切り替え機能を使用する場合のmsgを追加したリポジトリです。

External Plannerの詳細内容については[📖Autoware.universe](https://github.com/Toyota/autoware_universe)を参照ください。

## 概要

外部のカスタムプランナー（External Planner）への切り替え機能を使用するために、
`tier4_planning_msgs/msg/Scenario.msg` に `External` 定数を追加しています。

#### `tier4_planning_msgs/msg/Scenario.msg`

| Constant    | Type     | Value         | Description           |
| ------------| -------- |  -----------  |  ---------------------| 	
| `EMPTY`     | `string` | `External`    | ExternalPlanner state |

## ライセンス

本プロジェクトは、元のAutoware.universeプロジェクトのライセンスに従います。<br>
詳細については [LICENSE](LICENSE) を参照してください。

## コントリビューション

本プロジェクトに関心をお持ちいただきありがとうございます。<br>
現在、外部からのPull Requestを受け付けるための体制・ガイドラインを整備中です（2026年内に開始予定）。<br>
それまでの間は、バグ報告や機能要望についてはIssueでお知らせいただけると助かります。

## 開発・保守メンバー

本プロジェクト は現在、以下のメンバーによって開発・保守されています。

* 宮原 康晃（トヨタ自動車㈱）
* 橋本 直也（トヨタ自動車㈱）
* 高橋 俊（トヨタ自動車㈱）
* 谷崎 大地（トヨタ自動車㈱）

## お問い合わせ

バグ報告や機能要望については、Issue を作成してください。
内容を確認のうえ、可能な範囲で対応いたします。
