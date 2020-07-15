# MAUT : Moon Age Updater for Twitter. 
日付から月齢を計算し, Twitter のアカウント名に月齢に応じた emoji 🌔 
を追加する Python スクリプト. 

## 使用方法
`update_profile.py` と同じディレクトリに `config.py` を作成し, 実行する. 
`config.py` は Twitter のアクセストークンなどを記したファイル. 

### config.py
以下のようにアカウント名を変更したいユーザのトークン等を記載する. 
```
CONSUMER_KEY = "xxxxxxxxxxxxxxxx"
CONSUMER_SECRET = "xxxxxxxxxxxxxxxxxxxxxxxxx"
ACCESS_TOKEN = "xxxxxxxxxxxxxxxxxxxxxxxxx"
ACCESS_TOKEN_SECRET = "xxxxxxxxxxxxxxxxxxxxxxxxx"
```

## 必要ライブラリ
* tweepy

## License
MIT License
