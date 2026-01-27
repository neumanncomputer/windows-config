# windows-settings

## **Crtl + Space**で入力言語を切り替える

**設定 > 時刻と言語 > 言語と地域 > Microsoft IME > キーとタッチとのカスタマイズ > キーの割り当て** で **Crtl + Space** に **IME-オン/オフ** を割り当てる。

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

## 本体JISキーボード と 外付けUSキーボード を併用できるようにする

> [!WARNING]
> 個人が作成したツールであるため利用には確認が必要となる。

1. [USkey2JP](https://ms-soft.jp/tools/uskey2jp/)からzipファイルをダウンロードし、解凍
2. USkey2JP.exeを実行
