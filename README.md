<h1 align="center">Centos7でのiptables設定</h1>

### firewalldを停止
```sh
$ systemctl stop firewalld
$ systemctl disable firewalld
$ systemctl status firewalld
```

### iptablesのインストール
```sh
$ yum -y install iptables-services
```

### iptablesの起動と自動起動の設定
```sh
$ systemctl start iptables
$ systemctl enable iptables
$ systemctl status iptables
```

### iptablesの設定
```sh
$ git clone centos7-iptables-setting
$ systemctl enable iptables
$ systemctl status iptables
```
