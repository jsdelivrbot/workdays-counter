# workdays-counter

## 概要

最終出社日までにあと何営業日あるのかをカウントして画面に表示します。

以下の日が休業日として、営業日カウントから除外されます。
- 土曜日
- 日曜日
- 祝日
- 振替休日
- 有給休暇等、自分で定義した休日

カウントは毎分自動で最新の情報に更新されます。

## 使い方
1. app.jsの先頭で、最終出社日と自分独自の休日を定義します
2. ローカルのindex.htmlをブラウザで開きます

## 背景

以前の職場を退職する際に、引き継ぎ等を円滑に進めるため、最終出社日まであと何営業日なのかを簡単に把握しようと思い作成しました。
