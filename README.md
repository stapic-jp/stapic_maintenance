# stapic-maintenance
メンテナンス画面をここで作成する

## これは何か？
メンテナンスはALBの固定レスポンスで返している。しかしながら、1024文字までしか対応していない。  
そのためiframeを使ってこのリポジトリのgithub pagesを表示することで以下の三つの条件を満たす。
- 無制限アクセスへの耐久性
- 無料
- リンクが変動しないこと

## 作り方
#### `stapic`の`infra/src/maintenance/body.html`を編集する。  
`<<finishtime>>`の部分にデプロイ時に入力する時間が入るため残しておく。  
デプロイ時に自動的にそこが変更された、index.htmlが作成されpushされる。   

[https://stapic-jp.github.io/stapic_maintenance/](https://stapic-jp.github.io/stapic_maintenance/)  

をオープンすることで最新版のindex.htmlは確認できる。

## メンテナンスページの表示の仕方
wikiを参照。
