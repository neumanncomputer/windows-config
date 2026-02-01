# windows-settings

## **Crtl + Space**で入力言語を切り替える

1. 設定アプリを起動  
2. **時刻と言語 > 言語と地域 > Microsoft IME > キーとタッチとのカスタマイズ > キーの割り当て > Crtl + Space** に **IME-オン/オフ** を割り当てる

## caps lockにctrlを割り当てる

> [!NOTE]
> PowerToys の Keyboard Manager で実施するのが理想だが、2026/1/27現在、caps lock キーなどのトグルキーを変更するとバグってしまうため不採用。

> [!WARNING]
> Ctrl2Cap は Microsoft のツールであるため信頼できるが、管理者権限でのインストールが必要

1. [Ctrl2Cap](https://learn.microsoft.com/ja-jp/sysinternals/downloads/ctrl2cap)をダウンロードし解凍
2. 管理者権限で開いたPower Shellで以下のコマンドを実行。

```shell
cd 解凍したフォルダ
.\ctrl2cap /install
```

## カーソルの色を反転する

1. 設定アプリを起動  
2. **アクセシビリティ > マウス ポインターとタッチ > マウス ポインターのスタイル** に反転色を割り当てる

## Power Toysで便利機能を設定する

1. PowerToysアプリを起動
2. 以下の機能をオンにする

### コマンド パレット

コマンド、アプリ、開発ツールに 1 つの高速ソリューションからアクセスするために使用できるクイックランチャー ユーティリティ

### PowerRename

一度に複数のファイルの名前をすばやく変更できる一括名前変更ツール

### PowerToys Warp

マウスポインターが画面の端に到達した際、壁を突き抜けるようにして 反対側の端からワープして出現させることができる

### マウスの検索

**アクティブ化の方法** に**マウスをシェイクする**を設定  
マウスを素早く動かすとポインターがハイライトされるので、ポインターを見失った時に見つけやすい。

### Image Resizer

File Explorerで選択した 1 つ以上のイメージ ファイルを右クリックし、メニューから **ImageResizer でサイズ変更** を選択して、画像処理ワークフローを効率化

## 本体JISキーボード と 外付けUSキーボード を併用できるようにする

> [!WARNING]
> 個人が作成したツールであるため利用には確認が必要となる。

1. [USkey2JP](https://ms-soft.jp/tools/uskey2jp/)からzipファイルをダウンロードし、解凍
2. USkey2JP.exeを実行
