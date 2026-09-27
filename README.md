# Health Data × ChatGPT Starter

Google Spreadsheetへ自分の健康データを1日1行で記録し、ChatGPT Projectから相談するための最小スターターです。

## これは何か

- 体重、睡眠、活動、食事の記録を1つの表へ置くためのテンプレート
- その表をChatGPT ProjectのSourceとして使い、普通の言葉で相談するための手順

## これは何ではないか

- 特定の人のHealth Systemを再現するもの
- 医療用ツールや診断ツール
- データを自動取得する連携システム
- 体重や健康状態を正確に予測する仕組み

## 必要なもの

- Google Account
- Google Spreadsheet
- ProjectとSourceを利用できるChatGPT環境
- 自分で記録できる健康データ

## Quick Start

1. `data/daily-template.csv` をGoogle Spreadsheetへ取り込みます。
2. まず試す場合は、`data/daily-sample.csv` を取り込みます。
3. ChatGPTでProjectを作成します。
4. SpreadsheetをProjectで利用できるSourceとして追加します。
5. `INSTRUCTIONS.md` の本文をProject Instructionsへ貼り付けます。
6. Project内で「今の状態どう？」と聞いてみます。

詳しい手順は [SETUP.md](SETUP.md) を参照してください。列の意味は [docs/DATA_FIELDS.md](docs/DATA_FIELDS.md)、扱い方の注意は [PRIVACY.md](PRIVACY.md) にあります。

ChatGPTのProject UIは変更されることがあります。このKitでは画面上のボタン位置よりも、Google SpreadsheetをProjectのSourceとして追加し、Instructionsを設定できる状態を基準に説明しています。

## 次にできること

食事・栄養データの入力を自動化したい場合は、別のNutrition Capture Kitを組み合わせる余地があります。このStarter自体は、手入力だけでも使える最小構成です。
