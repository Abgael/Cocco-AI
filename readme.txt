/*-------------------------- こっこAI ⊂(*'ω')⊃ README --------------------------*/

■内容物
・AI.lua			本体です。特に手を加える必要はありません。
・cocco_tool.hta	各種設定エディタ・状態モニタなどが利用できる総合補助ツールです。
・readme.txt		このファイルです。

------------------------------------------------------------------------------------

▲AI起動(ホムンクルス召喚)後に自動で生成されるファイル
・Mob.lua				Mobごとの設定を保存するファイルです。※設定でファイル名が変更可能です。
・Message.lua			状態モニタに状態を反映するためのファイルです。
・Timer.lua				スキルの時間管理用ファイルです。自動でスキルを使用すると生成されます。

▲任意の操作で生成されるファイル
・Set.lua				設定エディタでホムンクルスごとの設定を作成すると生成されるファイルです。
・Friend.lua			友達登録をすると生成されるファイルです。
・FriendName.ini		友達ファイルエディタで名前を付けると生成されるファイルです。


◎ディレクトリ指定について
USER_AIディレクトリにこっこAIをインストールする場合は、
ご自分で「Cocco_USER_AI.txt」というファイルを作成してください。

　右クリック -> 新規作成 -> テキストドキュメント -> 「新規テキスト ドキュメント」を「Cocco_USER_AI」に変更


★エディタが上手く起動しない時のOSの設定について
・最初に右クリックでプロパティを開き、ブロックを解除してください。
・OSの設定により、プログラムの通信をブロックしていることがあります。
　通信を許可するように変更してください。
　http://windows.microsoft.com/ja-jp/windows/communicate-through-windows-firewall#1TC=windows-7

・コンピュータにログインしているアカウントの権限が、管理者ではない場合、
　Program Filesのファイル操作が出来ないことがあります。
　cocco_tool.htaを管理者権限で起動してみてください。

☆その他わからないことがあれば、まずは「よくある質問」をご確認ください。
　http://cocco.privatemoon.jp/qa/

====================================================
   制作：PrivateMoon 冠月ユウ
   CoccoAI - http://cocco.privatemoon.jp/
====================================================