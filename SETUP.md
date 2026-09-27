# Setup

## 1. Google Spreadsheetを作る

Google Driveで新しいGoogle Spreadsheetを作成します。`data/daily-template.csv` をインポートするか、1行目の列名をコピーします。

最初は使い方を試すため、完全な架空データである `data/daily-sample.csv` を取り込んでも構いません。

## 2. 数日分を記録する

記録できる項目だけを、1日につき1行入力します。すべての列を毎日埋める必要はありません。日付は `YYYY-MM-DD` 形式にそろえます。

## 3. ChatGPTでProjectを作る

ChatGPTで新しいProjectを作成します。名前は「健康相談」など、分かりやすい任意の名前で構いません。

Google SpreadsheetをProjectのSourceとして使うため、SpreadsheetをSourceとして追加できるProjectを使用してください。ChatGPTの画面やProjectの種類の表示は、OSやアプリのバージョンによって異なる場合があります。固定されたボタン名や位置ではなく、Sourceを追加できる状態かどうかを基準に進めます。

## 4. SpreadsheetをSourceとして追加する

Projectで利用できるSourceの追加画面から、作成したGoogle Spreadsheetを選択します。画面上の名称や利用可能な連携方法は、利用環境によって異なる場合があります。

追加後、Projectから表の内容を参照できるかを確認してください。

## 5. Instructionsを設定する

[INSTRUCTIONS.md](INSTRUCTIONS.md) の「Base Instructions」を、Project Instructionsへそのまま貼り付けます。

## 6. 健康相談用のChatを作る

Project内で新しいChatを開きます。最初は次のように聞いてみてください。

> 今の状態どう？

## 7. iPhoneから使う

同じProjectとChatをiPhoneで開けば、外出先でも短い質問で相談できます。利用前に、Sourceへの共有設定とProjectの共有範囲を確認してください。

## Sourceを追加できない場合

2026-09-27にMac版ChatGPTでdogfoodingした際、最初に作成したProjectではSpreadsheetをSourceとして追加できず、作り直したProjectでは利用できました。ChatGPTのProject UIはバージョンやOSによって変わる可能性があります。

SpreadsheetをSourceとして追加できない場合は、作成したProjectの種類と、そのProjectで利用可能なSourceを確認してください。特定のOSやProject種別で必ず同じ挙動になるとは限りません。

## 完了した状態

次の状態になれば、Starterのセットアップは完了です。

1. Google Spreadsheetがある。
2. 健康データが入っている。
3. ChatGPT Projectがある。
4. Spreadsheetが利用可能なSourceとして登録されている。
5. Generic Instructionsが設定されている。
6. Project内に健康相談Chatがある。
7. 「今の状態どう？」と質問できる。

## 更新のしかた

このStarterは手入力を前提にしています。新しい日付の行を追加または更新した後、ChatGPTがその変更をいつ参照できるかは、利用中のSource連携の状態に依存します。重要な判断の前には、必要なら最新の表を確認してください。
