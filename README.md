# 概要
レベルアッププログラミングの静的サイト公開の練習リポジトリです。


# プロジェクト管理

このリポジトリのタスクはプロジェクトにて管理されています。
タスクの追加・進行・完了時は、プロジェクトの更新も忘れないようにしてください。

https://github.com/hitorigods/lp-practice-static/projects/1


# サイトのURL

https://hitorigods.shop/

/public_html/hitorigods.shop/


# SSH接続
```
$ ssh hitorigods@s223.xrea.com
```

# GitでSSHのパスフレーズ入力を省略

```
$ eval `ssh-agent`
$ ssh-add '/c/Users/HIRO/.ssh/id_rsa'
```


# SSH接続IP許可

https://cp.xrea.com/site/tools/

グローバルIPアドレスが変わった場合

# リリース手順

プロジェクトディレクトリで以下のコマンドを実行

```
sh deploy.sh
```
