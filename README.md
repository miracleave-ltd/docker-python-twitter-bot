# 1.VSCodeを起動する
<br><br>
# 2.Dockerの拡張機能をインストール
VSCodeの拡張機能から「Remote - Containers」を検索し、インストールする。
<br>
※Remote - Containersは、Docker上でVSCodeによる開発を可能とする
<img width="1440" alt="2" src="https://user-images.githubusercontent.com/65474365/84446080-b6727580-ac7f-11ea-989e-d7d73da45d37.png">
<br><br>
# 3.プロジェクト作成
プロジェクトとなるフォルダを作成し、VSCodeで開く。
<br><br>
# 4.HelloWrold作成
動作確認用に、HelloWroldを記述した.pyファイルを作成する。
<br><br>
# 5.Dockerへの接続
①VSCodeの左下の緑チェックマークを押下する
<br>
②上部に表示される検索蘭から「Remote-Containers: Open Folder in Container...」を選択する。
<br>
③3.で作成したプロジェクトをOpenする。
<br>
④上部に表示される検索蘭から「Python 3」を選択する。
<img width="1439" alt="5" src="https://user-images.githubusercontent.com/65474365/84446663-f84feb80-ac80-11ea-9c06-c3189ed9d5dd.png">
<br><br>
# 6.Dockerファイルの修正
Dockerファイルが自動生成されていることを確認し、配布したDockerファイルで上書きする。
<br>
※配布したDockerファイルには、Pythonのプラグインなどが含まれている
<img width="1438" alt="6" src="https://user-images.githubusercontent.com/65474365/84447624-73b29c80-ac83-11ea-8062-0aa9dc9c04cc.png">
<br><br>
# 7.ビルド
①VSCodeの左下の緑チェックマークを押下する
<br>
②「Remote-Containers: Rebuild Container」を選択する。
<br><br>
# 8.デバックと実行
①左タブから「実行」を選択
<br>
②”デバックまたは実行可能なファイルを開きます”から、4.で作成したファイルを選択。
<br>
③必要であればブレークポイントを置き、「実行とデバック」ボタンを押下し、上部検索欄から「Python File」を選択する。
<br>
④ブレークポイントが止まり、Hello Worldが表示されれば成功。
<img width="1043" alt="12" src="https://user-images.githubusercontent.com/65474365/84448388-84641200-ac85-11ea-9cdf-abe4ad0cf011.png">
<br><br>
