common-ansible-role
============================================================

# 概要

OS初期インストール時の共通設定

1. 共通パッケージのインストール
2. selinuxの無効化
3. firewallの無効化
4. networkの基本設定
5. ntpの設定
6. ユーザを作成

# 動作確認済み環境

- CentOS6
- CentOS7

# 設定

    common_ntp_server     # ntpサーバ
    common_user.name      # 作成するユーザ名
    common_user.passsword # 作成するユーザのパスワード(ハッシュ値)
    common_user.uid       # 作成するユーザのuid
    common_user.group     # 作成するユーザのgroup名
    common_user.gid       # 作成するユーザのgid

# 依存関係

依存するroleはありません
