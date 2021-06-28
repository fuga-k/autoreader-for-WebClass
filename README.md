## autoreader-for-WebClass
(完全に内輪ネタです)
WebClassのレポート提出したときに受信箱に来る，「レポートを受け取りました」ってやつ既読にするのめんどくさくないですか？
ってことで自動で全部既読にしてくれる簡単なプログラムを作ってみました。
**内容を判別するわけではないので，課題や考査についての重要なお知らせとかが来てても問答無用で全部既読にします。**
そのせいで重要なお知らせを見逃しても僕の責任ではありません。**自己責任**でお願いします。

## Requirements
+ python3
+ selenium
+ ChromeDriver(`pip`などでインストールし，Pathを通さなくて済む方法を推奨。ここではその方法で書いています。)

## 使い方
1. `config.py`に学籍番号と共通パスワードを書いておく。
1. 同じディレクトリに`autoreader.py`を置いて実行。Chromeが起動して勝手に画面が操作されます。楽しい。

## 補足
ChromeDriverであればWindows,Macともに動作確認済み。`webdriver.Safari`を使えばSafariでも行けるはずだけどうまくいかなかったので諦めた。
