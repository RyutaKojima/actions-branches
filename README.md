# actions-branches

```
main
 ↑pull request
develop
 ↓               future-feature
 ↓checkout        ↑pull request(※)
topic branches===============
```

- topic→future へのPR作成時に、topic→developのPRも自動で作成する

- ブランチとCI/CD接続先
  - main: 本番環境
  - develop: ステージング環境
  - future-feature: リリース機能事前確認環境


