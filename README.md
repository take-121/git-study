# git study
## git チュートリアル
### 1. clone
```
# リポジトリ名のディレクトリが作成される
git clone 'コピーしたURL'
```

### 2. リモートのマスターブランチへpushするまでの流れ
```
# ステージングへ
git add 'file'

# メッセージを入れてコミットする
git commit -m

# pushするときの情報を確認
git remote -v

# リモートのマスターブランチへpush
git push origin
```
