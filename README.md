# 1.最新情報をローカルに持ってくる
```rb:ターミナル
git fetch origin main
```

# 2.ローカルのファイルが最新の状態に更新する
```rb:ターミナル
git merge origin/main
```

*** ここからはプッシュの仕方


# 1.コードをプッシュする場合
```rb:ターミナル
git add -p
```

# 1.ファイルをプッシュする場合
```rb:ターミナル
git add ファイル名
```

# 2.コミットする
```rb:ターミナル
git commit -m "〇〇"
```

# 3.プッシュする
```rb:ターミナル
git push origin ブランチ名
```