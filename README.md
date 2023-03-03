# VS2022-Copilot-Demo-Snippet
GitHub Copilot をデモする際に使えそうなコードスニペットを VS2022 にまとめて登録するための XML ファイル

## 使い方
1. 本リポジトリにある MyCopilotDemoSnippets.snippet ファイルをダウンロードします
1. Visual Studio 2022 を開いて、[ツール] > [コードスニペットマネージャー] を開きます
1. [インポート] ボタンをクリックします
1. 最初の手順でダウンロードした MyCopilotDemoSnippets.snippet ファイルを選択します
1. [コードスニペットのインポート] ダイアログの右ペインから、スニペットの追加先として [My Code Snippets] を選択して、登録を完了します
1. C# のコンソールアプリプロジェクトを作成しコード中の任意のクラスの中で "copi001" とタイプして Tab キーを二回押すと、コメント行が追加されます
1. さらに改行すると、Copilot が有効の環境では、自動的にコードの候補が表示され、Tab キーで確定できます

## コードスニペットの追加の方法
自分の都合のいいようにコードスニペットをカスタマイズしたい場合、下記のドキュメントに従って行いましょう！
https://learn.microsoft.com/ja-jp/visualstudio/ide/walkthrough-creating-a-code-snippet?view=vs-2022
