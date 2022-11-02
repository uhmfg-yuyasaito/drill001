# Project UH-Drill

### djangoインストールコマンド後
- フォルダ所有権の変更
- 静止ファイルの集約
- サービス再起動

### フォルダ所有権の変更
```
$ sudo chown -R YOUR_ACCOUNT_NAME:YOUR_ACCOUNT_NAME src/
```

### 静止ファイルの集約
```
$ docker-compose exec django /bin/bash
$ ./manage.py collectstatic
```

### サービス再起動
```
$ docker-compose restart
```

### 参考サイト
```
https://qiita.com/ftoshiki/items/1cb250a27bbbbaa5c719
```
