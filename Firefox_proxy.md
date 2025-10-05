# FireFoxのプロキシ・VPNの導入方法
## 1.プロキシの拡張機能をダウンロード、導入
まず、このファイル[proxy.zip](https://github.com/user-attachments/files/22709592/proxy.zip)をダウンロード、解凍(展開)し、中のwindscribe~~.xpiを確認する。
次に、FireFoxを起動し、右上の「拡張機能」をクリックし、その中の「拡張機能を管理」をクリックする。すると、拡張機能のページに飛ぶ。
そのページの右上にある歯車をクリックし、「ファイルからアドオンをインストール」をクリックし、先ほど確認したwindscribe~~.xpiを選択する。
<img width="972" height="428" alt="image" src="https://github.com/user-attachments/assets/e5ef4465-7b25-45e1-a32d-e86c7c2f2bb0" />
## 2.拡張機能のセットアップ
もう一度「拡張機能」をクリックすると、Windscribeという拡張機能が入っていることがわかる。
Windscribeをクリックすると、ログインが必要と出てくるため、Windscribeのホームページでアカウント登録をし、ログインする(skymenueによってブロックされている可能性があるため、アカウント登録はスマホなどで）
ログインした後、左上の三本からConnectionの項目へ行き、その中のProxyPorを9443から443へ変更する(これをしないとブロックされてしまう）。

<img width="301" height="428" alt="image" src="https://github.com/user-attachments/assets/f8dec522-ac54-4339-bd16-c12e6932b9c6" />

## 3.拡張機能を使う
電源ボタンのようなものをクリックすると、左にON,000,0000,000のようなものと、AutoPilotと表示されます。この状態であればブロックされているサイトへのアクセスが可能になります。

