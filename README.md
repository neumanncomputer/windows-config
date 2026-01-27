# windows-settings

## caps lockにctrlを割り当てる
※PowerToysのKeyboard Managerで実施するのが理想だが、2026/1/27現在、caps lockキーなどのトグルキーを変更するとバグってしまう。

1. [Ctrl2Cap](https://learn.microsoft.com/ja-jp/sysinternals/downloads/ctrl2cap)をダウンロードし解凍
2. 管理者権限で開いたPower Shellで以下のコマンドを実行。
```shell
cd 解凍したフォルダ
.\ctrl2cap /install
```

## **Crtl + Space**で入力言語を切り替える

**設定 > 時刻と言語 > 言語と地域 > Microsoft IME > キーとタッチとのカスタマイズ > キーの割り当て** で **Crtl + Space** に **IME-オン/オフ** を割り当てる。
