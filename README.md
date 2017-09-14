# studyLaravel

#### 概要
自分用のLaravelのローカル仮想環境を構築するVagrantとAnsible設定ファイルです。

#### 実行方法
事前にPCに、VirtualBox、Vagrant、Ansibleをインストールして下さい。
また、VirtualBoxでは"ubuntu/xenial64"を使用しているので、下記コマンドなどでboxを追加しておいて下さい。

```$ vagrant box add ubuntu/xenial64```

下記コマンドを実行することで"192.168.33.13"で確認出来るローカル仮想環境が作られます。

```$ vagrant up```

#### 編集方法
Laravelのファイルは"/var/www/laravel/"に存在するのでよしなに編集して下さい。  
また、Nginxで動いているため"/etc/nginx/"の中もよしなに編集して下さい。

#### 検証環境
- OS X El Capitan
- Google Chrome Version 58.0.3029.110 (64-bit)