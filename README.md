# popapex
Simple C++ cheats for Apex Legends (Linux Steam version).

検出
すべての敵がブラッドハウンド スキャンで強調表示されます。照準を合わせて敵が 50 メートル以上離れている場合、コースティック ビジョンを使用して強調表示され、壁越しに見えないようにして、壁への射撃を防ぎます。

ノリコイル
垂直方向と水平方向の武器反動の調整可能な減少。左シフトを押したままにして一時的に無効にすることができます。

エイムボット
CQC 戦闘用の調整可能なエイムボット。骨ではなく敵の位置の作品。横向きのみ動作します。左シフトを押したままにして一時的に無効にすることができます。

## Requirements
1. Linux OS with X11
2. g++ compiler (Ubuntu 11.2.0-19ubuntu1) 11.2.0 or higher)
3. Git

セットアップと実行方法

1.ターミナルを開き、以下を実行してチートソースコードをダウンロードします

git clone https://github.com/Teirq/popapex


２．ダウンロードしたフォルダに移動します

cd myapex


３．コードをコンパイルする

g++ Main.cpp -lX11


４．Steam に移動し、Apex Legends を実行します

5.チートを実行します（メモリの読み取りと書き込みにはsudoアクセスが必要です）

sudo ./a.out

You should now see a lot of lines being printed saying "LOOP OK...." which means the cheat is running fine. Enjoy.













