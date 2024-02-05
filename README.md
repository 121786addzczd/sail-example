# wslでLaravel

## 環境構築
sail-exampleディレクトリにいる状態で以下コマンド実行

```shell
./vendor/bin/sail up -d
```

logファイルに書き込み権限与える
```shell
sudo chown -R ユーザー名:ユーザー名 .
```

## alias設定
./vendor/bin/sailを毎回入力するのは大変です。そのため、今回ショートカットコマンドを設定します。
```shell
echo "alias sail='vendor/bin/sail'" >> ~/.bashrc
```