# Como Lite
macOS用デストップアプリケーション。
最前面アプリが切り替わると、そのアプリのウインドウもすべて最前面にします。つまり、Classic Mac OSと同じ挙動を再現するものです。

## インストール
Como Lite.appをアプリケーションフォルダなどへコピーします。
* システム要件：OS X 10.9以降
* ダウンロード後、Como Lite.appを選択し、右クリックメニューの［開く］を選択してください。

## 使い方
Como Lite.appを起動しておくだけです。
* メニューバー［Como Lite > 環境設定...］で、対象をFinderのみに設定できます。

## 詳細
Como Liteは、CarbonアプリだったComoのCocoa版です。Carbon版Comoは設定が複雑すぎたので、Cocoa版は必要最小限に絞ってLiteとしました。

ソースは[Xojo](https://www.xojo.com/)のプロジェクトファイルです。アプリ切換はNSNotificationObserverで検知しており、ここだけ[MBS Plugin](https://www.monkeybreadsoftware.de/xojo/)（有償ライセンス）を使用しています。