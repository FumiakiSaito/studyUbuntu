# ubuntsLesson

## vagrantで環境構築

### boxを追加
```
vagrant box add ubuntu/trusty64
```

### Vagrantファイルを作成
```
vagrant init
```

### Vagrantファイルを編集しboxを設定

```
 # config.vm.box = "base"
  config.vm.box = "ubuntu/trusty64"
```

### 仮想サーバ起動
```
vagrant up
```

### sshできるようにconfigに追加
```
vagrant ssh-config --host ubunts >> ~/.ssh/config
```

### ssh接続
```
ssh ubunts
```

